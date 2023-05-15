# Currency-Symbol
Get All Countries Code , with Currency Code and Currency Symbol


CREATE TABLE `countries` (
  `id` bigint(20) UNSIGNED NOT NULL,
  `name` varchar(255) COLLATE utf8mb4_unicode_ci DEFAULT NULL,
  `shortname` varchar(255) COLLATE utf8mb4_unicode_ci DEFAULT NULL,
  `countrycode` int(11) DEFAULT NULL,
  `flag` varchar(255) COLLATE utf8mb4_unicode_ci DEFAULT NULL,
  `currency` varchar(3) CHARACTER SET utf8mb4 DEFAULT NULL,
  `currency_symbol` varchar(5) COLLATE utf8mb4_unicode_ci DEFAULT NULL,
  `created_at` timestamp NULL DEFAULT NULL,
  `updated_at` timestamp NULL DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_unicode_ci;



INSERT INTO `countries` (`id`, `name`, `shortname`, `countrycode`, `flag`, `currency`, `currency_symbol`, `created_at`, `updated_at`) VALUES
(1, 'Afghanistan', 'AFG', 93, 'AF', 'AFN', '؋', NULL, NULL),
(2, 'Albania', 'ALB', 355, 'AL', 'ALL', 'Lek', NULL, NULL),
(3, 'Algeria', 'DZA', 213, 'DZ', 'DZD', 'DA', NULL, NULL),
(4, 'American Samoa', 'ASM', 1684, 'AS', 'USD', '$', NULL, NULL),
(5, 'Andorra', 'AND', 376, 'AD', 'EUR', '€', NULL, NULL),
(6, 'Angola', 'AGO', 244, 'AO', 'AOA', 'Kz', NULL, NULL),
(7, 'Anguilla', 'AIA', 1264, 'AI', 'XCD', '$', NULL, NULL),
(8, 'Antigua and Barbuda', 'ATG', 1268, 'AG', 'XCD', '$', NULL, NULL),
(9, 'Argentina', 'ARG', 54, 'AR', 'ARS', '$', NULL, NULL),
(10, 'Armenia', 'ARM', 374, 'AM', 'AMD', '֏', NULL, NULL),
(11, 'Aruba', 'ABW', 297, 'AW', 'AWG', 'ƒ', NULL, NULL),
(12, 'Australia', 'AUS', 61, 'AU', 'AUD', '$', NULL, NULL),
(13, 'Austria', 'AUT', 43, 'AT', 'EUR', '€', NULL, NULL),
(14, 'Azerbaijan', 'AZE', 994, 'AZ', 'AZN', 'ман', NULL, NULL),
(15, 'Bahamas', 'BHS', 1242, 'BS', 'BSD', '$', NULL, NULL),
(16, 'Bahrain', 'BHR', 973, 'BH', 'BHD', 'BD', NULL, NULL),
(17, 'Bangladesh', 'BGD', 880, 'BD', 'BDT', '৳', NULL, NULL),
(18, 'Barbados', 'BRB', 1246, 'BB', 'BBD', '$', NULL, NULL),
(19, 'Belarus', 'BLR', 375, 'BY', 'BYR', 'p.', NULL, NULL),
(20, 'Belgium', 'BEL', 32, 'BE', 'EUR', '€', NULL, NULL),
(21, 'Belize', 'BLZ', 501, 'BZ', 'BZD', 'BZ$', NULL, NULL),
(22, 'Benin', 'BEN', 229, 'BJ', 'XOF', 'CFA', NULL, NULL),
(23, 'Bermuda', 'BMU', 1441, 'BM', 'BMD', '$', NULL, NULL),
(24, 'Bhutan', 'BTN', 975, 'BT', 'BTN', 'Nu.', NULL, NULL),
(25, 'Bolivia', 'BOL', 591, 'BO', 'BOB', '$b', NULL, NULL),
(26, 'Bosnia and Herzegovina', 'BIH', 387, 'BA', 'BAM', 'KM', NULL, NULL),
(27, 'Botswana', 'BWA', 267, 'BW', 'BWP', 'P', NULL, NULL),
(28, 'Brazil', 'BRA', 55, 'BR', 'BRL', 'R$', NULL, NULL),
(29, 'Brunei Darussalam', 'BRN', 673, 'BN', 'BND', '$', NULL, NULL),
(30, 'Bulgaria', 'BGR', 359, 'BG', 'BGN', 'лв', NULL, NULL),
(31, 'Burkina Faso', 'BFA', 226, 'BF', 'XOF', 'CFA', NULL, NULL),
(32, 'Burundi', 'BDI', 257, 'BI', 'BIF', 'FBu', NULL, NULL),
(33, 'Cambodia', 'KHM', 855, 'KH', 'KHR', '៛', NULL, NULL),
(34, 'Cameroon', 'CMR', 237, 'CM', 'XAF', 'FCFA', NULL, NULL),
(35, 'Canada', 'CAN', 1, 'CA', 'CAD', '$', NULL, NULL),
(36, 'Cape Verde', 'CPV', 238, 'CV', 'CVE', 'Esc', NULL, NULL),
(37, 'Cayman Islands', 'CYM', 1345, 'KY', 'KYD', '$', NULL, NULL),
(38, 'Central African Republic', 'CAF', 236, 'CF', 'XAF', 'FCFA', NULL, NULL),
(39, 'Chad', 'TCD', 235, 'TD', 'XAF', 'FCFA', NULL, NULL),
(40, 'Chile', 'CHL', 56, 'CL', 'CLP', '$', NULL, NULL),
(41, 'China', 'CHN', 86, 'CN', 'CNY', '¥', NULL, NULL),
(42, 'Colombia', 'COL', 57, 'CO', 'COP', '$', NULL, NULL),
(43, 'Comoros', 'COM', 269, 'KM', 'KMF', 'CF', NULL, NULL),
(44, 'Congo', 'COG', 242, 'CG', 'CDF', 'FC', NULL, NULL),
(45, 'Congo, the Democratic Republic of the', 'COD', 242, 'CD', 'XAF', 'FCFA', NULL, NULL),
(46, 'Cook Islands', 'COK', 682, 'CK', 'NZD', '$', NULL, NULL),
(47, 'Costa Rica', 'CRI', 506, 'CR', 'CRC', '₡', NULL, NULL),
(48, 'Cote DIvoire', 'CIV', 225, 'CI', 'XOF', 'CFA', NULL, NULL),
(49, 'Croatia', 'HRV', 385, 'HR', 'HRK', 'kn', NULL, NULL),
(50, 'Cuba', 'CUB', 53, 'CU', 'CUP', '₱', NULL, NULL),
(51, 'Cyprus', 'CYP', 357, 'CY', 'EUR', '€', NULL, NULL),
(52, 'Czech Republic', 'CZE', 420, 'CZ', 'CZK', 'Kč', NULL, NULL),
(53, 'Denmark', 'DNK', 45, 'DK', 'DKK', 'kr', NULL, NULL),
(54, 'Djibouti', 'DJI', 253, 'DJ', 'DJF', 'Fdj', NULL, NULL),
(55, 'Dominica', 'DMA', 1767, 'DM', 'XCD', '$', NULL, NULL),
(56, 'Dominican Republic', 'DOM', 1809, 'DO', 'DOP', 'RD$', NULL, NULL),
(57, 'Ecuador', 'ECU', 593, 'EC', 'USD', '$', NULL, NULL),
(58, 'Egypt', 'EGY', 20, 'EG', 'EGP', '£', NULL, NULL),
(59, 'El Salvador', 'SLV', 503, 'SV', 'SVC', '$', NULL, NULL),
(60, 'Equatorial Guinea', 'GNQ', 240, 'GQ', 'XAF', 'FCFA', NULL, NULL),
(61, 'Eritrea', 'ERI', 291, 'ER', 'ERN', 'Nkf', NULL, NULL),
(62, 'Estonia', 'EST', 372, 'EE', 'EEK', 'KR', NULL, NULL),
(63, 'Ethiopia', 'ETH', 251, 'ET', 'ETB', 'Br', NULL, NULL),
(64, 'Falkland Islands (Malvinas)', 'FLK', 500, 'FK', 'FKP', '£', NULL, NULL),
(65, 'Faroe Islands', 'FRO', 298, 'FO', 'FOK', 'KR\r\n', NULL, NULL),
(66, 'Fiji', 'FJI', 679, 'FJ', 'FJD', '$', NULL, NULL),
(67, 'Finland', 'FIN', 358, 'FI', 'EUR', '€', NULL, NULL),
(68, 'France', 'FRA', 33, 'FR', 'EUR', '€', NULL, NULL),
(69, 'French Guiana', 'GUF', 594, 'GF', 'EUR', '€', NULL, NULL),
(70, 'French Polynesia', 'PYF', 689, 'PF', 'XPF', '₣', NULL, NULL),
(71, 'Gabon', 'GAB', 241, 'GA', 'XAF', 'FCFA', NULL, NULL),
(72, 'Gambia', 'GMB', 220, 'GM', 'GMD', 'D', NULL, NULL),
(73, 'Georgia', 'GEO', 995, 'GE', 'GEL', 'ლ', NULL, NULL),
(74, 'Germany', 'DEU', 49, 'DE', 'EUR', '€', NULL, NULL),
(75, 'Ghana', 'GHA', 233, 'GH', 'GHC', '¢', NULL, NULL),
(76, 'Gibraltar', 'GIB', 350, 'GI', 'GIP', '£', NULL, NULL),
(77, 'Greece', 'GRC', 30, 'GR', 'EUR', '€', NULL, NULL),
(78, 'Greenland', 'GRL', 299, 'GL', 'DKK', 'kr', NULL, NULL),
(79, 'Grenada', 'GRD', 1473, 'GD', 'XCD', '$', NULL, NULL),
(80, 'Guadeloupe', 'GLP', 590, 'GP', 'EUR', '€', NULL, NULL),
(81, 'Guam', 'GUM', 1671, 'GU', 'USD', '$', NULL, NULL),
(82, 'Guatemala', 'GTM', 502, 'GT', 'GTQ', 'Q', NULL, NULL),
(83, 'Guinea', 'GIN', 224, 'GN', 'GNF', 'FG', NULL, NULL),
(84, 'Guinea-Bissau', 'GNB', 245, 'GW', 'GWP', 'Gfr', NULL, NULL),
(85, 'Guyana', 'GUY', 592, 'GY', 'GYD', '$', NULL, NULL),
(86, 'Haiti', 'HTI', 509, 'HT', 'USD', '$', NULL, NULL),
(87, 'Holy See (Vatican City State)', 'VAT', 39, 'VA', 'EUR', '€', NULL, NULL),
(88, 'Honduras', 'HND', 504, 'HN', 'HNL', 'L', NULL, NULL),
(89, 'Hong Kong', 'HKG', 852, 'HK', 'HKD', '$', NULL, NULL),
(90, 'Hungary', 'HUN', 36, 'HU', 'HUF', 'Ft', NULL, NULL),
(91, 'Iceland', 'ISL', 354, 'IS', 'ISK', 'kr', NULL, NULL),
(92, 'India', 'IND', 91, 'IN', 'INR', '₹', NULL, NULL),
(93, 'Indonesia', 'IDN', 62, 'ID', 'IDR', 'Rp', NULL, NULL),
(94, 'Iran, Islamic Republic of', 'IRN', 98, 'IR', 'IRR', '﷼', NULL, NULL),
(95, 'Iraq', 'IRQ', 964, 'IQ', 'IQD', 'ع.د', NULL, NULL),
(96, 'Ireland', 'IRL', 353, 'IE', 'EUR', '€', NULL, NULL),
(97, 'Israel', 'ISR', 972, 'IL', 'ILS', '₪', NULL, NULL),
(98, 'Italy', 'ITA', 39, 'IT', 'EUR', '€', NULL, NULL),
(99, 'Jamaica', 'JAM', 1876, 'JM', 'JMD', 'J$', NULL, NULL),
(100, 'Japan', 'JPN', 81, 'JP', 'JPY', '¥', NULL, NULL),
(101, 'Jordan', 'JOR', 962, 'JO', 'JOD', 'د.ا', NULL, NULL),
(102, 'Kazakhstan', 'KAZ', 7, 'KZ', 'KZT', 'лв', NULL, NULL),
(103, 'Kenya', 'KEN', 254, 'KE', 'KES', 'Ksh', NULL, NULL),
(104, 'Kiribati', 'KIR', 686, 'KI', 'AUD', '$', NULL, NULL),
(105, 'Korea, Democratic Peoples Republic of', 'PRK', 850, 'KP', 'KPW', '₩', NULL, NULL),
(106, 'Korea, Republic of', 'KOR', 82, 'KR', 'KRW', '₩', NULL, NULL),
(107, 'Kuwait', 'KWT', 965, 'KW', 'KWD', 'د.ك', NULL, NULL),
(108, 'Kyrgyzstan', 'KGZ', 996, 'KG', 'KGS', 'лв', NULL, NULL),
(109, 'Lao Peoples Democratic Republic', 'LAO', 856, 'LA', 'LAK', '₭', NULL, NULL),
(110, 'Latvia', 'LVA', 371, 'LV', 'EUR', '€', NULL, NULL),
(111, 'Lebanon', 'LBN', 961, 'LB', 'LBP', '£', NULL, NULL),
(112, 'Lesotho', 'LSO', 266, 'LS', 'LSL', 'L', NULL, NULL),
(113, 'Liberia', 'LBR', 231, 'LR', 'LRD', 'L$', NULL, NULL),
(114, 'Libyan Arab Jamahiriya', 'LBY', 218, 'LY', 'LYD', 'ل.د', NULL, NULL),
(115, 'Liechtenstein', 'LIE', 423, 'LI', 'CHF', 'CHF', NULL, NULL),
(116, 'Lithuania', 'LTU', 370, 'LT', 'LTL', 'Lt', NULL, NULL),
(117, 'Luxembourg', 'LUX', 352, 'LU', 'EUR', '€', NULL, NULL),
(118, 'Macao', 'MAC', 853, 'MO', 'MOP', 'MOP$', NULL, NULL),
(119, 'Macedonia, the Former Yugoslav Republic of', 'MKD', 389, 'MK', 'MKD', 'ден', NULL, NULL),
(120, 'Madagascar', 'MDG', 261, 'MG', 'MGF', '	MF', NULL, NULL),
(121, 'Malawi', 'MWI', 265, 'MW', 'MWK', 'MK', NULL, NULL),
(122, 'Malaysia', 'MYS', 60, 'MY', 'MYR', 'RM', NULL, NULL),
(123, 'Maldives', 'MDV', 960, 'MV', 'MVR', 'Rf', NULL, NULL),
(124, 'Mali', 'MLI', 223, 'ML', 'XOF', 'CFA', NULL, NULL),
(125, 'Malta', 'MLT', 356, 'MT', 'MTL', '£M', NULL, NULL),
(126, 'Marshall Islands', 'MHL', 692, 'MH', 'USD', '$', NULL, NULL),
(127, 'Martinique', 'MTQ', 596, 'MQ', 'EUR', '€', NULL, NULL),
(128, 'Mauritania', 'MRT', 222, 'MR', 'MRO', 'UM', NULL, NULL),
(129, 'Mauritius', 'MUS', 230, 'MU', 'MUR', '₨', NULL, NULL),
(130, 'Mexico', 'MEX', 52, 'MX', 'MXN', '$', NULL, NULL),
(131, 'Micronesia, Federated States of', 'FSM', 691, 'FM', 'USD', '$', NULL, NULL),
(132, 'Moldova, Republic of', 'MDA', 373, 'MD', 'MDL', 'L', NULL, NULL),
(133, 'Monaco', 'MCO', 377, 'MC', 'EUR', '€', NULL, NULL),
(134, 'Mongolia', 'MNG', 976, 'MN', 'MNT', '₮', NULL, NULL),
(135, 'Montserrat', 'MSR', 1664, 'MS', 'XCD', '$', NULL, NULL),
(136, 'Morocco', 'MAR', 212, 'MA', 'MAD', 'MAD', NULL, NULL),
(137, 'Mozambique', 'MOZ', 258, 'MZ', 'MZM', 'MT', NULL, NULL),
(138, 'Myanmar', 'MMR', 95, 'MM', 'MMK', 'K', NULL, NULL),
(139, 'Namibia', 'NAM', 264, 'NA', 'NAD', '$', NULL, NULL),
(140, 'Nauru', 'NRU', 674, 'NR', 'AUD', '$', NULL, NULL),
(141, 'Nepal', 'NPL', 977, 'NP', 'NPR', '₨', NULL, NULL),
(142, 'Netherlands', 'NLD', 31, 'NL', 'EUR', '€', NULL, NULL),
(143, 'New Caledonia', 'NCL', 687, 'NC', 'XPF', '₣', NULL, NULL),
(144, 'New Zealand', 'NZL', 64, 'NZ', 'NZD', '$', NULL, NULL),
(145, 'Nicaragua', 'NIC', 505, 'NI', 'NIO', 'C$', NULL, NULL),
(146, 'Niger', 'NER', 227, 'NE', 'XOF', 'CFA', NULL, NULL),
(147, 'Nigeria', 'NGA', 234, 'NG', 'NGN', '₦', NULL, NULL),
(148, 'Niue', 'NIU', 683, 'NU', 'NZD', '$', NULL, NULL),
(149, 'Norfolk Island', 'NFK', 672, 'NF', 'AUD', '$', NULL, NULL),
(150, 'Northern Mariana Islands', 'MNP', 1670, 'MP', 'USD', '$', NULL, NULL),
(151, 'Norway', 'NOR', 47, 'NO', 'NOK', 'kr', NULL, NULL),
(152, 'Oman', 'OMN', 968, 'OM', 'OMR', '﷼', NULL, NULL),
(153, 'Pakistan', 'PAK', 92, 'PK', 'PKR', '₨', NULL, NULL),
(154, 'Palau', 'PLW', 680, 'PW', 'USD', '$', NULL, NULL),
(155, 'Panama', 'PAN', 507, 'PA', 'USD', '$', NULL, NULL),
(156, 'Papua New Guinea', 'PNG', 675, 'PG', 'PGK', 'K', NULL, NULL),
(157, 'Paraguay', 'PRY', 595, 'PY', 'PYG', 'Gs', NULL, NULL),
(158, 'Peru', 'PER', 51, 'PE', 'PEN', 'S/.', NULL, NULL),
(159, 'Philippines', 'PHL', 63, 'PH', 'PHP', 'Php', NULL, NULL),
(160, 'Pitcairn', 'PCN', 0, 'PN', 'NZD', '$', NULL, NULL),
(161, 'Poland', 'POL', 48, 'PL', 'PLN', 'zł', NULL, NULL),
(162, 'Portugal', 'PRT', 351, 'PT', 'EUR', '€', NULL, NULL),
(163, 'Puerto Rico', 'PRI', 1787, 'PR', 'USD', '$', NULL, NULL),
(164, 'Qatar', 'QAT', 974, 'QA', 'QAR', '﷼', NULL, NULL),
(165, 'Reunion', 'REU', 262, 'RE', 'EUR', '€', NULL, NULL),
(166, 'Romania', 'ROU', 40, 'RO', 'ROL', 'lei', NULL, NULL),
(167, 'Russian Federation', 'RUS', 70, 'RU', 'RUR', 'K', NULL, NULL),
(168, 'Rwanda', 'RWA', 250, 'RW', 'RWF', 'R₣', NULL, NULL),
(169, 'Saint Helena', 'SHN', 290, 'SH', 'SHP', '£', NULL, NULL),
(170, 'Saint Kitts and Nevis', 'KNA', 1869, 'KN', 'XCD', '$', NULL, NULL),
(171, 'Saint Lucia', 'LCA', 1758, 'LC', 'XCD', '$', NULL, NULL),
(172, 'Saint Pierre and Miquelon', 'SPM', 508, 'PM', 'USD', '$', NULL, NULL),
(173, 'Saint Vincent and the Grenadines', 'VCT', 1784, 'VC', 'XCD', '$', NULL, NULL),
(174, 'Samoa', 'WSM', 684, 'WS', 'WST', 'WS$', NULL, NULL),
(175, 'San Marino', 'SMR', 378, 'SM', 'EUR', '€', NULL, NULL),
(176, 'Sao Tome and Principe', 'STP', 239, 'ST', 'STD', 'Db', NULL, NULL),
(177, 'Saudi Arabia', 'SAU', 966, 'SA', 'SAR', '﷼', NULL, NULL),
(178, 'Senegal', 'SEN', 221, 'SN', 'XOF', 'CFA', NULL, NULL),
(179, 'Seychelles', 'SYC', 248, 'SC', 'SCR', '₨', NULL, NULL),
(180, 'Sierra Leone', 'SLE', 232, 'SL', 'SLL', 'Le', NULL, NULL),
(181, 'Singapore', 'SGP', 65, 'SG', 'SGD', '$', NULL, NULL),
(182, 'Slovakia', 'SVK', 421, 'SK', 'EUR', '€', NULL, NULL),
(183, 'Slovenia', 'SVN', 386, 'SI', 'EUR', '€', NULL, NULL),
(184, 'Solomon Islands', 'SLB', 677, 'SB', 'SBD', '$', NULL, NULL),
(185, 'Somalia', 'SOM', 252, 'SO', 'SOS', 'S', NULL, NULL),
(186, 'South Africa', 'ZAF', 27, 'ZA', 'ZAR', 'R', NULL, NULL),
(187, 'Spain', 'ESP', 34, 'ES', 'EUR', '€', NULL, NULL),
(188, 'Sri Lanka', 'LKA', 94, 'LK', 'LKR', '₨', NULL, NULL),
(189, 'Sudan', 'SDN', 249, 'SD', 'SDG', 'ج.س', NULL, NULL),
(190, 'Suriname', 'SUR', 597, 'SR', 'SRG', 'ƒ‎', NULL, NULL),
(191, 'Svalbard and Jan Mayen', 'SJM', 47, 'SJ', 'NOK', 'kr', NULL, NULL),
(192, 'Swaziland', 'SWZ', 268, 'SZ', 'SZL', 'L', NULL, NULL),
(193, 'Sweden', 'SWE', 46, 'SE', 'SEK', 'kr', NULL, NULL),
(194, 'Switzerland', 'CHE', 41, 'CH', 'CHF', 'CHF', NULL, NULL),
(195, 'Syrian Arab Republic', 'SYR', 963, 'SY', 'SYP', '£', NULL, NULL),
(196, 'Taiwan, Province of China', 'TWN', 886, 'TW', 'TWD', 'NT$', NULL, NULL),
(197, 'Tajikistan', 'TJK', 992, 'TJ', 'TJS', 'ЅM', NULL, NULL),
(198, 'Tanzania, United Republic of', 'TZA', 255, 'TZ', 'TZS', 'TSh', NULL, NULL),
(199, 'Thailand', 'THA', 66, 'TH', 'THB', '฿', NULL, NULL),
(200, 'Togo', 'TGO', 228, 'TG', 'XOF', 'CFA', NULL, NULL),
(201, 'Tokelau', 'TKL', 690, 'TK', 'NZD', '$', NULL, NULL),
(202, 'Tonga', 'TON', 676, 'TO', 'TOP', 'T$', NULL, NULL),
(203, 'Trinidad and Tobago', 'TTO', 1868, 'TT', 'TTD', 'TT$', NULL, NULL),
(204, 'Tunisia', 'TUN', 216, 'TN', 'TND', 'DT', NULL, NULL),
(205, 'Turkey', 'TUR', 90, 'TR', 'TRY', '₺', NULL, NULL),
(206, 'Turkmenistan', 'TKM', 7370, 'TM', 'TMM', 'T', NULL, NULL),
(207, 'Turks and Caicos Islands', 'TCA', 1649, 'TC', 'USD', '$', NULL, NULL),
(208, 'Tuvalu', 'TUV', 688, 'TV', 'AUD', '$', NULL, NULL),
(209, 'Uganda', 'UGA', 256, 'UG', 'UGX', 'USh', NULL, NULL),
(210, 'Ukraine', 'UKR', 380, 'UA', 'UAH', '₴', NULL, NULL),
(211, 'United Arab Emirates', 'ARE', 971, 'AE', 'AED', 'د.إ', NULL, NULL),
(212, 'United Kingdom', 'GBR', 44, 'GB', 'GBP', '£', NULL, NULL),
(213, 'United States', 'USA', 1, 'US', 'USS', '$', NULL, NULL),
(214, 'Uruguay', 'URY', 598, 'UY', 'UYU', '$U', NULL, NULL),
(215, 'Uzbekistan', 'UZB', 998, 'UZ', 'UZS', 'лв', NULL, NULL),
(216, 'Vanuatu', 'VUT', 678, 'VU', 'VUV', 'VT', NULL, NULL),
(217, 'Venezuela', 'VEN', 58, 'VE', 'VEF', 'Bs', NULL, NULL),
(218, 'Viet Nam', 'VNM', 84, 'VN', 'VND', '₫', NULL, NULL),
(219, 'Virgin Islands, British', 'VGB', 1284, 'VG', 'USD', '$', NULL, NULL),
(220, 'Virgin Islands, U.s.', 'VIR', 1340, 'VI', 'USD', '$', NULL, NULL),
(221, 'Wallis and Futuna', 'WLF', 681, 'WF', 'XPF', '₣', NULL, NULL),
(222, 'Western Sahara', 'ESH', 212, 'EH', 'MAD', 'MAD', NULL, NULL),
(223, 'Yemen', 'YEM', 967, 'YE', 'YER', '﷼', NULL, NULL),
(224, 'Zambia', 'ZMB', 260, 'ZM', 'ZMW', 'ZK', NULL, NULL),
(225, 'Zimbabwe', 'ZWE', 263, 'ZW', 'ZWD', 'Z$', NULL, NULL);
