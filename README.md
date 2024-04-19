# Indonesian Area Data | Data Wilayah Indonesia - JSON Format Per Level (Raw Data)
This Data is a comprehensive dataset encompassing administrative divisions such as provinces (provinsi), regencies (kabupaten), districts (kecamatan), and villages (kelurahan/desa). Compiled from official sources like the Badan Pusat Statistik (BPS) and the Kementerian Dalam Negeri (Kemendagri). 

This information is structured in JSON format, enabling efficient access and utilization. With this dataset, users can navigate Indonesia's administrative hierarchy, facilitating various applications such as demographic analysis, resource allocation, and urban planning.

---

Data ini adalah kumpulan data komprehensif yang mencakup pembagian administratif seperti provinsi (provinsi), kabupaten (kabupaten), kecamatan (kecamatan), dan desa (kelurahan/desa). Dihimpun dari sumber resmi seperti Badan Pusat Statistik (BPS) dan Kementerian Dalam Negeri (Kemendagri).

Informasi ini disusun dalam format JSON, memungkinkan akses dan pemanfaatan yang efisien. Dengan kumpulan data ini, pengguna dapat menavigasi hierarki administratif Indonesia, memfasilitasi berbagai aplikasi seperti analisis demografi, alokasi sumber daya, dan perencanaan kota.

## Area Level - Latest Data Get on `April, 19 2024`
|Level|Items|
|---|---|
|Provinces (Provinsi)|38|
|Regencies (Kabupaten)|514|
|Districts (Kecamatan)|7288|
|Villages (Kelurahan/Desa)|84210|

## Sample Data

1. Provinces (Provinsi)
```json
{
    "11": "ACEH",
    "12": "SUMATERA UTARA",
    "13": "SUMATERA BARAT",
    "14": "RIAU",
    "15": "JAMBI",
    "16": "SUMATERA SELATAN",
    "17": "BENGKULU",
    "18": "LAMPUNG",
    "19": "KEPULAUAN BANGKA BELITUNG",
    "21": "KEPULAUAN RIAU",
    "31": "DKI JAKARTA",
    "32": "JAWA BARAT",
    "33": "JAWA TENGAH",
    "34": "DI YOGYAKARTA",
    "35": "JAWA TIMUR",
    "36": "BANTEN",
    "51": "BALI",
    "52": "NUSA TENGGARA BARAT",
    "53": "NUSA TENGGARA TIMUR",
    "61": "KALIMANTAN BARAT",
    "62": "KALIMANTAN TENGAH",
    "63": "KALIMANTAN SELATAN",
    "64": "KALIMANTAN TIMUR",
    "65": "KALIMANTAN UTARA",
    "71": "SULAWESI UTARA",
    "72": "SULAWESI TENGAH",
    "73": "SULAWESI SELATAN",
    "74": "SULAWESI TENGGARA",
    "75": "GORONTALO",
    "76": "SULAWESI BARAT",
    "81": "MALUKU",
    "82": "MALUKU UTARA",
    "91": "PAPUA BARAT",
    "92": "PAPUA BARAT DAYA",
    "94": "PAPUA",
    "95": "PAPUA SELATAN",
    "96": "PAPUA TENGAH",
    "97": "PAPUA PEGUNUNGAN"
}
```

2. Regencies (Kabupaten)
```json
// Data on Province: DI YOGYAKARTA (34)
{
    "01": "KAB. KULON PROGO",
    "02": "KAB. BANTUL",
    "03": "KAB. GUNUNGKIDUL",
    "04": "KAB. SLEMAN",
    "71": "KOTA YOGYAKARTA"
}
```

3. Districts (Kecamatan)
```json
// Data on 
// Province: DI YOGYAKARTA (34)
// Regency : KAB. SLEMAN (04)
{
    "010": "MOYUDAN",
    "020": "MINGGIR",
    "030": "SEYEGAN",
    "040": "GODEAN",
    "050": "GAMPING",
    "060": "MLATI",
    "070": "DEPOK",
    "080": "BERBAH",
    "090": "PRAMBANAN",
    "100": "KALASAN",
    "110": "NGEMPLAK",
    "120": "NGAGLIK",
    "130": "SLEMAN",
    "140": "TEMPEL",
    "150": "TURI",
    "160": "PAKEM",
    "170": "CANGKRINGAN"
}
```

4. Villages (Kelurahan/Desa)
```json
// Data on 
// Province: DI YOGYAKARTA (34)
// Regency : KAB. SLEMAN (04)
// District: DEPOK (070)
{
    "001": "CATUR TUNGGAL",
    "002": "MAGUWOHARJO",
    "003": "CONDONG CATUR"
}
```