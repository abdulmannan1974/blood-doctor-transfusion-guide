// Blood🩸Doctor Transfusion Guide - Interactive Application
// Based on Bio-Rad Blood Group Antibodies Reference

const bloodGroupData = {
    abo: {
        name: "ABO System",
        code: "ISBT 001",
        class: "abo",
        antibodies: [
            {
                name: "Anti-A",
                symbol: "ABO1",
                igM: "Yes",
                igG: "Yes",
                saline: "Yes",
                iat: "Yes for IgM component",
                papain: "Yes for IgG component",
                dosage: "May show",
                complement: "↑↑",
                hdfn: "Yes, some hemolytic",
                htr: "No to moderate",
                clinicalSig: "No to severe",
                freqCaucasian: "43",
                freqBlack: "27",
                freqOthers: "Asians: 28, Mexicans: 28",
                remarks: "Naturally occurring antibody. Can cause immediate or delayed hemolytic transfusion reactions."
            },
            {
                name: "Anti-B",
                symbol: "ABO2",
                igM: "Yes",
                igG: "Yes",
                saline: "Yes",
                iat: "Yes for IgM component",
                papain: "Yes for IgG component",
                dosage: "May show",
                complement: "↑↑",
                hdfn: "Yes, some hemolytic",
                htr: "No to moderate",
                clinicalSig: "No to severe",
                freqCaucasian: "9",
                freqBlack: "20",
                freqOthers: "Asians: 27, Mexicans: 13",
                remarks: "Naturally occurring antibody. Can cause immediate or delayed hemolytic transfusion reactions."
            },
            {
                name: "Anti-A,B",
                symbol: "ABO3",
                igM: "Yes",
                igG: "Yes",
                saline: "Yes",
                iat: "Yes for IgM component",
                papain: "Yes for IgG component",
                dosage: "May show",
                complement: "↑↑",
                hdfn: "Rare",
                htr: "No to severe",
                clinicalSig: "None to mild/delayed",
                freqCaucasian: "56",
                freqBlack: "51",
                freqOthers: "Asians: 57, Mexicans: 45",
                remarks: "Only produced by group O individuals. Cannot be separated into anti-A and anti-B."
            },
            {
                name: "Anti-A₁",
                symbol: "ABO4",
                igM: "Yes",
                igG: "Rare",
                saline: "Yes",
                iat: "Rare",
                papain: "Rare",
                dosage: "No",
                complement: "↑↑",
                hdfn: "Rare",
                htr: "No",
                clinicalSig: "None to mild/delayed",
                freqCaucasian: "34",
                freqBlack: "19",
                freqOthers: "Asians: 27",
                remarks: "Frequency: 1-2% in blood group A₂, 25% in blood group A₂B, 99% in blood group Aₓ."
            }
        ]
    },
    h: {
        name: "H Blood Group System",
        code: "ISBT 018",
        class: "abo",
        antibodies: [
            {
                name: "Anti-H",
                symbol: "H1",
                igM: "Yes",
                igG: "Rare",
                saline: "Yes",
                iat: "Rare",
                papain: "Rare",
                dosage: "No",
                complement: "↑↑",
                hdfn: "Some",
                htr: "Possible in Oh mothers",
                clinicalSig: "No to severe in Oh and H+w",
                freqCaucasian: "99.9",
                freqBlack: "99.9",
                freqOthers: "All populations: 99.9",
                remarks: "Alloanti-H is present in the serum of Bombay (Oh) and Para-Bombay (H+w) people. O cells show the strongest antigen expression, A₁B cells the weakest."
            }
        ]
    },
    mns: {
        name: "MNS System",
        code: "ISBT 002",
        class: "mns",
        antibodies: [
            {
                name: "Anti-M",
                symbol: "MNS1",
                igM: "Yes",
                igG: "Yes",
                saline: "IgM and IgG",
                iat: "Rare",
                papain: "↓↓",
                dosage: "Yes",
                complement: "Yes",
                hdfn: "No (except in extremely rare cases)",
                htr: "No (except in extremely rare cases)",
                clinicalSig: "No (except in extremely rare cases)",
                freqCaucasian: "78",
                freqBlack: "74",
                freqOthers: "",
                remarks: "Many examples are naturally-occurring. May be pH dependent. More common in children, and in patients with bacterial infections."
            },
            {
                name: "Anti-N",
                symbol: "MNS2",
                igM: "Yes",
                igG: "Yes",
                saline: "IgM and IgG",
                iat: "Rare",
                papain: "↓↓",
                dosage: "Yes",
                complement: "Yes",
                hdfn: "No",
                htr: "No",
                clinicalSig: "No",
                freqCaucasian: "72",
                freqBlack: "75",
                freqOthers: "",
                remarks: "Many examples are naturally-occurring. Rare N-S-s-U- individuals make an antibody that reacts with N on GPA and GPB."
            },
            {
                name: "Anti-S",
                symbol: "MNS3",
                igM: "Some",
                igG: "Most",
                saline: "Some",
                iat: "Most",
                papain: "V",
                dosage: "Yes",
                complement: "Yes",
                hdfn: "Some",
                htr: "No to severe (rare)",
                clinicalSig: "No to moderate (rare)",
                freqCaucasian: "55",
                freqBlack: "31",
                freqOthers: "",
                remarks: "The S antigen is sensitive to trace amounts of chlorine."
            },
            {
                name: "Anti-s",
                symbol: "MNS4",
                igM: "Yes",
                igG: "Yes",
                saline: "Some",
                iat: "Most",
                papain: "V",
                dosage: "Yes",
                complement: "Yes",
                hdfn: "Rare",
                htr: "No to severe (rare)",
                clinicalSig: "No to mild (rare)",
                freqCaucasian: "89",
                freqBlack: "93",
                freqOthers: "",
                remarks: "Reacts often by IAT after incubation at RT or lower. A pH of 6.0 enhances the reactivity of some anti-s."
            },
            {
                name: "Anti-U",
                symbol: "MNS5",
                igM: "Yes",
                igG: "No",
                saline: "Yes",
                iat: "Yes",
                papain: "Yes",
                dosage: "No",
                complement: "No",
                hdfn: "Mild to severe",
                htr: "Mild to severe",
                clinicalSig: "Mild to severe",
                freqCaucasian: "99.9",
                freqBlack: "99",
                freqOthers: "",
                remarks: "Autoantibody has been identified to cause WAIHA in rare cases."
            }
        ]
    },
    rh: {
        name: "Rh System",
        code: "ISBT 004",
        class: "rh",
        antibodies: [
            {
                name: "Anti-D",
                symbol: "RH1",
                igM: "Some",
                igG: "Most",
                saline: "Rare",
                iat: "Yes",
                papain: "↑↑",
                dosage: "No",
                complement: "Extremely rare",
                hdfn: "Mild to severe",
                htr: "Mild to severe/immediate or delayed",
                clinicalSig: "Mild to severe/immediate or delayed",
                freqCaucasian: "85",
                freqBlack: "92",
                freqOthers: "Asians: 99, Native Americans: 99",
                remarks: "Most clinically significant antibody after ABO. Occurs frequently with anti-C."
            },
            {
                name: "Anti-C",
                symbol: "RH2",
                igM: "Yes",
                igG: "Yes",
                saline: "Rare",
                iat: "Yes",
                papain: "↑↑",
                dosage: "Yes",
                complement: "Yes",
                hdfn: "No",
                htr: "Mild",
                clinicalSig: "Mild to severe/immediate or delayed",
                freqCaucasian: "68",
                freqBlack: "27",
                freqOthers: "Asians: 93",
                remarks: "Anti-C is often found in antibody mixtures, especially with anti-G or anti-D."
            },
            {
                name: "Anti-E",
                symbol: "RH3",
                igM: "Yes",
                igG: "Yes",
                saline: "Some",
                iat: "Yes",
                papain: "↑↑",
                dosage: "Yes",
                complement: "Yes",
                hdfn: "No",
                htr: "Mild",
                clinicalSig: "Mild to severe/immediate or delayed",
                freqCaucasian: "29",
                freqBlack: "22",
                freqOthers: "Asians: 39",
                remarks: "Occurs frequently with anti-c."
            },
            {
                name: "Anti-c",
                symbol: "RH4",
                igM: "Some",
                igG: "Most",
                saline: "Rare",
                iat: "Yes",
                papain: "↑↑",
                dosage: "Yes",
                complement: "Yes",
                hdfn: "No",
                htr: "Mild to severe",
                clinicalSig: "Mild to severe/immediate or delayed",
                freqCaucasian: "80",
                freqBlack: "98",
                freqOthers: "Asians: 47",
                remarks: "Occurs frequently with anti-E."
            },
            {
                name: "Anti-e",
                symbol: "RH5",
                igM: "Some",
                igG: "Most",
                saline: "Rare",
                iat: "Yes",
                papain: "↑↑",
                dosage: "Yes",
                complement: "Yes",
                hdfn: "No",
                htr: "Rare, usually mild",
                clinicalSig: "Mild to moderate/delayed/hemoglobinuria",
                freqCaucasian: "98",
                freqBlack: "98",
                freqOthers: "Asians: 96",
                remarks: "Occurs frequently with anti-C."
            },
            {
                name: "Anti-Cʷ",
                symbol: "RH8",
                igM: "Yes",
                igG: "Yes",
                saline: "Yes",
                iat: "Yes",
                papain: "↑↑",
                dosage: "Yes",
                complement: "No",
                hdfn: "Mild to moderate",
                htr: "Mild to severe/immediate or delayed",
                clinicalSig: "Mild to severe/immediate or delayed",
                freqCaucasian: "2",
                freqBlack: "1",
                freqOthers: "Finns: 4, Latvians: 9",
                remarks: "Most Cʷ+ are C+; rare examples are C-."
            }
        ]
    },
    kell: {
        name: "Kell System",
        code: "ISBT 006",
        class: "kell",
        antibodies: [
            {
                name: "Anti-K",
                symbol: "KEL1",
                igM: "Some",
                igG: "Most",
                saline: "Some",
                iat: "Yes",
                papain: "=",
                dosage: "No",
                complement: "Rare",
                hdfn: "Mild to severe (rare)",
                htr: "Mild to severe/delayed/hemolytic",
                clinicalSig: "Mild to severe/delayed/hemolytic",
                freqCaucasian: "9",
                freqBlack: "2",
                freqOthers: "Asians: rare, Iranian Jews: 12, Arabs: 25",
                remarks: "Anti-K may not react well by LISS procedures. Some bacteria trigger production of IgM anti-K."
            },
            {
                name: "Anti-k",
                symbol: "KEL2",
                igM: "Rare",
                igG: "Most",
                saline: "Rare",
                iat: "Yes",
                papain: "=",
                dosage: "No",
                complement: "No",
                hdfn: "Mild to severe (rare)",
                htr: "Mild to moderate/delayed",
                clinicalSig: "Mild to moderate/delayed",
                freqCaucasian: "99.8",
                freqBlack: "100",
                freqOthers: "",
                remarks: "Rare but clinically significant."
            },
            {
                name: "Anti-Kpᵃ",
                symbol: "KEL3",
                igM: "Yes",
                igG: "Very rare",
                saline: "Yes",
                iat: "Yes",
                papain: "=",
                dosage: "No",
                complement: "No",
                hdfn: "Mild to severe",
                htr: "Mild to moderate/delayed",
                clinicalSig: "Mild to moderate/delayed",
                freqCaucasian: "2",
                freqBlack: "<0.01",
                freqOthers: "",
                remarks: "In the presence of Kpᵃ, other inherited Kell antigens are suppressed (cis-modifying effect). Anti-Kpᵃ appears often combined with anti-K."
            },
            {
                name: "Anti-Kpᵇ",
                symbol: "KEL4",
                igM: "Rare",
                igG: "Yes",
                saline: "Rare",
                iat: "Yes",
                papain: "=",
                dosage: "No",
                complement: "No",
                hdfn: "Mild to moderate",
                htr: "No to moderate/delayed",
                clinicalSig: "No to moderate/delayed",
                freqCaucasian: "100",
                freqBlack: "100",
                freqOthers: "",
                remarks: "Sera containing anti-Kpᵇ often contain anti-K."
            },
            {
                name: "Anti-Jsᵃ",
                symbol: "KEL6",
                igM: "Rare",
                igG: "Most",
                saline: "Rare",
                iat: "Yes to ↑",
                papain: "=",
                dosage: "No",
                complement: "No",
                hdfn: "Mild to severe",
                htr: "No to moderate/delayed",
                clinicalSig: "No to moderate/delayed",
                freqCaucasian: "<0.01",
                freqBlack: "20",
                freqOthers: "",
                remarks: "Predominantly found in individuals of African descent."
            },
            {
                name: "Anti-Jsᵇ",
                symbol: "KEL7",
                igM: "Yes",
                igG: "Very rare",
                saline: "Yes to ↑",
                iat: "Yes",
                papain: "=",
                dosage: "No",
                complement: "No",
                hdfn: "Mild to severe",
                htr: "Mild to moderate/delayed",
                clinicalSig: "Mild to moderate/delayed",
                freqCaucasian: "100",
                freqBlack: "99",
                freqOthers: "",
                remarks: "Rare antibody."
            }
        ]
    },
    lewis: {
        name: "Lewis System",
        code: "ISBT 007",
        class: "lewis",
        antibodies: [
            {
                name: "Anti-Leᵃ",
                symbol: "LE1",
                igM: "Most",
                igG: "Some",
                saline: "Yes",
                iat: "Some",
                papain: "↑↑",
                dosage: "No",
                complement: "Yes, some hemolytic",
                hdfn: "No (one mild case)",
                htr: "No (rare cases of hemolytic reactions)",
                clinicalSig: "No (rare cases of hemolytic reactions)",
                freqCaucasian: "22",
                freqBlack: "23",
                freqOthers: "",
                remarks: "Anti-Leᵃ and anti-Leᵇ in conjunction are frequently naturally occurring antibodies made by Le(a-b-) people."
            },
            {
                name: "Anti-Leᵇ",
                symbol: "LE2",
                igM: "Most",
                igG: "Some",
                saline: "Yes",
                iat: "Some",
                papain: "↑↑",
                dosage: "No",
                complement: "Yes, some hemolytic",
                hdfn: "No",
                htr: "No",
                clinicalSig: "No",
                freqCaucasian: "72",
                freqBlack: "55",
                freqOthers: "",
                remarks: "Two kinds exist: anti-LeᵇH (LE4) reacting with group O and A₂ Le(b+) RBCs, and anti-LeᵇL reacting with all Le(b+) RBCs."
            }
        ]
    },
    duffy: {
        name: "Duffy System",
        code: "ISBT 008",
        class: "duffy",
        antibodies: [
            {
                name: "Anti-Fyᵃ",
                symbol: "FY1",
                igM: "Rare",
                igG: "Yes",
                saline: "Very rare",
                iat: "Yes",
                papain: "↓↓",
                dosage: "Yes",
                complement: "Some",
                hdfn: "Rare",
                htr: "Mild to severe (rare)",
                clinicalSig: "Mild to severe (rare)/immediate/delayed",
                freqCaucasian: "66",
                freqBlack: "10",
                freqOthers: "Asians: 99, Thais: 97",
                remarks: "Clinically significant. Can cause delayed hemolytic transfusion reactions."
            },
            {
                name: "Anti-Fyᵇ",
                symbol: "FY2",
                igM: "Very rare",
                igG: "Yes",
                saline: "Very rare",
                iat: "Yes",
                papain: "↓↓",
                dosage: "Yes",
                complement: "Some",
                hdfn: "Rare",
                htr: "Mild (rare)",
                clinicalSig: "Mild to severe (rare)/immediate (rare)/delayed",
                freqCaucasian: "83",
                freqBlack: "23",
                freqOthers: "Chinese: 9.2, Asians: 18.5, Thais: 31",
                remarks: "Clinically significant."
            },
            {
                name: "Anti-Fy3",
                symbol: "FY3",
                igM: "Yes",
                igG: "Yes",
                saline: "Yes",
                iat: "Yes",
                papain: "↓",
                dosage: "No",
                complement: "Rare",
                hdfn: "Mild (rare)",
                htr: "Mild to moderate/immediate (rare)/delayed/hemolytic",
                clinicalSig: "Mild to moderate/immediate (rare)/delayed/hemolytic",
                freqCaucasian: "100",
                freqBlack: "32",
                freqOthers: "Asians: 99.9, Yemeni Jews: 99",
                remarks: "Made by Fy(a-b-) individuals."
            }
        ]
    },
    kidd: {
        name: "Kidd System",
        code: "ISBT 009",
        class: "kidd",
        antibodies: [
            {
                name: "Anti-Jkᵃ",
                symbol: "JK1",
                igM: "Yes, many IgG + IgM",
                igG: "Yes, many IgG + IgM",
                saline: "Rare",
                iat: "Yes",
                papain: "↑",
                dosage: "Yes",
                complement: "Some",
                hdfn: "Yes if IgM present, some hemolytic",
                htr: "Mild to moderate (rare)",
                clinicalSig: "No to severe/immediate or delayed/hemolytic",
                freqCaucasian: "77",
                freqBlack: "92",
                freqOthers: "Asians: 72",
                remarks: "Anti-Jkᵃ deteriorates in vitro and in vivo. Can cause severe delayed hemolytic transfusion reactions."
            },
            {
                name: "Anti-Jkᵇ",
                symbol: "JK2",
                igM: "Yes, many IgG + IgM",
                igG: "Yes, many IgG + IgM",
                saline: "Rare",
                iat: "Yes",
                papain: "↑",
                dosage: "Yes",
                complement: "Some",
                hdfn: "Yes if IgM present, some hemolytic",
                htr: "No to mild (rare)",
                clinicalSig: "No to severe/immediate or delayed/hemolytic",
                freqCaucasian: "74",
                freqBlack: "49",
                freqOthers: "Asians: 76",
                remarks: "Anti-Jkᵇ deteriorates in vitro and in vivo. Can cause severe delayed hemolytic transfusion reactions."
            },
            {
                name: "Anti-Jk3",
                symbol: "JK3",
                igM: "Rare",
                igG: "Yes",
                saline: "Rare",
                iat: "Yes",
                papain: "↑",
                dosage: "Yes",
                complement: "Yes, some hemolytic",
                hdfn: "No to mild",
                htr: "No to severe/immediate or delayed",
                clinicalSig: "No to severe/immediate or delayed",
                freqCaucasian: "100",
                freqBlack: "100",
                freqOthers: "Polynesians, Finns: >99",
                remarks: "Made by Jk(a-b-) individuals."
            }
        ]
    },
    lutheran: {
        name: "Lutheran System",
        code: "ISBT 005",
        class: "lutheran",
        antibodies: [
            {
                name: "Anti-Luᵃ",
                symbol: "LU1",
                igM: "Yes",
                igG: "Yes",
                saline: "Most",
                iat: "Some to ↓",
                papain: "=",
                dosage: "Yes",
                complement: "Rare",
                hdfn: "No to mild (rare)",
                htr: "No",
                clinicalSig: "No",
                freqCaucasian: "8",
                freqBlack: "5",
                freqOthers: "",
                remarks: "Characteristic reaction picture of 'loose' agglutinates. Sera containing anti-Luᵃ often also contain HLA antibodies."
            },
            {
                name: "Anti-Luᵇ",
                symbol: "LU2",
                igM: "Yes",
                igG: "Yes",
                saline: "Some",
                iat: "Most to ↓",
                papain: "=",
                dosage: "Yes",
                complement: "Rare",
                hdfn: "Mild",
                htr: "Mild to moderate",
                clinicalSig: "Mild to moderate",
                freqCaucasian: "99.8",
                freqBlack: "99.8",
                freqOthers: "All populations: 99.8",
                remarks: "Rare but can be clinically significant."
            },
            {
                name: "Anti-Lu3",
                symbol: "LU3",
                igM: "Yes",
                igG: "No",
                saline: "Yes",
                iat: "Yes",
                papain: "=",
                dosage: "No",
                complement: "Rare",
                hdfn: "No data",
                htr: "No data",
                clinicalSig: "No data",
                freqCaucasian: "100",
                freqBlack: "100",
                freqOthers: "All populations: 100",
                remarks: "Anti-Lu3 is only made by immunized individuals of the rare recessive type Lu(a-b-)."
            }
        ]
    },
    p1pk: {
        name: "P1PK & GLOB Systems",
        code: "ISBT 003, 028",
        class: "p1pk",
        antibodies: [
            {
                name: "Anti-P1",
                symbol: "P1PK1",
                igM: "Yes",
                igG: "Rare",
                saline: "Yes",
                iat: "Very rare",
                papain: "↑↑",
                dosage: "No",
                complement: "Rare",
                hdfn: "No",
                htr: "No to moderate/delayed (rare)",
                clinicalSig: "No to moderate/delayed (rare)",
                freqCaucasian: "79",
                freqBlack: "94",
                freqOthers: "Cambodian, Vietnamese: 20",
                remarks: "There is considerable variation in the strength of P1 expression on RBCs."
            },
            {
                name: "Anti-P",
                symbol: "GLOB1",
                igM: "Yes",
                igG: "Yes",
                saline: "Some",
                iat: "Some",
                papain: "↑↑",
                dosage: "No",
                complement: "Yes, some hemolytic",
                hdfn: "No to mild (in Pᵏ mothers with anti-P)",
                htr: "No to severe (rare)",
                clinicalSig: "No to severe (rare)",
                freqCaucasian: ">99.9",
                freqBlack: ">99.9",
                freqOthers: "All populations: >99.9",
                remarks: "Autoanti-P exists as a biphasic autohemolysin in PCH, detected by the Donath-Landsteiner test."
            },
            {
                name: "Anti-PP1Pᵏ (Tjᵃ)",
                symbol: "",
                igM: "Yes",
                igG: "Some",
                saline: "Some",
                iat: "Some",
                papain: "↑↑",
                dosage: "No",
                complement: "Yes, some hemolytic",
                hdfn: "Yes",
                htr: "Yes",
                clinicalSig: "Yes",
                freqCaucasian: "100",
                freqBlack: "100",
                freqOthers: "100",
                remarks: "Alloantibody in sera of p⁻ people may cause complete hemolysis in fresh serum. Potential cause of early abortion."
            }
        ]
    },
    diego: {
        name: "Diego System",
        code: "ISBT 010",
        class: "diego",
        antibodies: [
            {
                name: "Anti-Diᵃ",
                symbol: "DI1",
                igM: "Yes (often IgG1 and IgG3)",
                igG: "Yes",
                saline: "Some",
                iat: "Yes",
                papain: "=",
                dosage: "No",
                complement: "Mild to severe",
                hdfn: "No to severe/delayed",
                htr: "No to severe/delayed",
                clinicalSig: "No to severe/delayed",
                freqCaucasian: "0.01",
                freqBlack: "0.01",
                freqOthers: "South American Indians: 2-54, Japanese: 12, Chinese: 5",
                remarks: "Predominantly found in individuals of Asian and South American descent."
            },
            {
                name: "Anti-Diᵇ",
                symbol: "DI2",
                igM: "Yes",
                igG: "Yes",
                saline: "Yes",
                iat: "Yes",
                papain: "=",
                dosage: "No",
                complement: "No",
                hdfn: "Mild",
                htr: "No to moderate/delayed",
                clinicalSig: "No to moderate/delayed",
                freqCaucasian: "100",
                freqBlack: "100",
                freqOthers: "Most populations: 100, Native Americans: 99",
                remarks: ""
            },
            {
                name: "Anti-Wrᵃ",
                symbol: "DI3",
                igM: "Yes",
                igG: "Yes",
                saline: "Yes",
                iat: "Yes",
                papain: "=",
                dosage: "No",
                complement: "Yes",
                hdfn: "Mild to severe",
                htr: "No to severe/immediate or delayed/hemolytic",
                clinicalSig: "No to severe/immediate or delayed/hemolytic",
                freqCaucasian: "<0.01",
                freqBlack: "<0.01",
                freqOthers: "All populations: <0.01",
                remarks: "Alloanti-Wrᵃ is often naturally-occurring and found in the serum of 1-2% of blood donors."
            }
        ]
    },
    yt: {
        name: "Yt (Cartwright) System",
        code: "ISBT 011",
        class: "yt",
        antibodies: [
            {
                name: "Anti-Ytᵃ",
                symbol: "YT1",
                igM: "Yes (some are IgG4)",
                igG: "Yes",
                saline: "V",
                iat: "Some",
                papain: "=",
                dosage: "No",
                complement: "No",
                hdfn: "No to moderate (rare)/delayed",
                htr: "No to moderate (rare)/delayed",
                clinicalSig: "No to moderate (rare)/delayed",
                freqCaucasian: ">99.8",
                freqBlack: ">99.8",
                freqOthers: "Israeli Jews: 98.6, Israeli Arabs: 97.6",
                remarks: "Experts agree that anti-Ytᵃ are often benign and antigen-negative blood may not need to be transfused."
            },
            {
                name: "Anti-Ytᵇ",
                symbol: "YT2",
                igM: "Yes",
                igG: "Yes",
                saline: "V",
                iat: "Yes",
                papain: "=",
                dosage: "No",
                complement: "No",
                hdfn: "No",
                htr: "No",
                clinicalSig: "No",
                freqCaucasian: "8",
                freqBlack: "8",
                freqOthers: "Europeans: 8, Israeli Jews: 21.3, Not found in Japanese",
                remarks: "Anti-Ytᵇ is rare and usually occurs in sera with other antibodies."
            }
        ]
    },
    xg: {
        name: "Xg System",
        code: "ISBT 012",
        class: "xg",
        antibodies: [
            {
                name: "Anti-Xgᵃ",
                symbol: "XG1",
                igM: "Rare",
                igG: "Most",
                saline: "Some",
                iat: "Most",
                papain: "↓↓",
                dosage: "Yes",
                complement: "Some",
                hdfn: "No",
                htr: "No",
                clinicalSig: "No",
                freqCaucasian: "89 (Females), 66 (Males)",
                freqBlack: "89 (Females), 66 (Males)",
                freqOthers: "",
                remarks: "X-linked inheritance pattern."
            }
        ]
    },
    dombrock: {
        name: "Dombrock System",
        code: "ISBT 014",
        class: "dombrock",
        antibodies: [
            {
                name: "Anti-Doᵃ",
                symbol: "DO1",
                igM: "Yes",
                igG: "Yes",
                saline: "Yes",
                iat: "Yes",
                papain: "↑",
                dosage: "Yes",
                complement: "Positive DAT but no clinical HDFN",
                hdfn: "Positive DAT but no clinical HDFN",
                htr: "Delayed and acute/hemolytic",
                clinicalSig: "Delayed and acute/hemolytic",
                freqCaucasian: "67",
                freqBlack: "55",
                freqOthers: "Japanese: 24, Thais: 14",
                remarks: "Anti-Doᵃ is notorious for disappearing in vivo."
            },
            {
                name: "Anti-Doᵇ",
                symbol: "DO2",
                igM: "Yes",
                igG: "Yes",
                saline: "Yes",
                iat: "Yes",
                papain: "↑",
                dosage: "Yes",
                complement: "Positive DAT but no clinical HDFN",
                hdfn: "Positive DAT but no clinical HDFN",
                htr: "Acute and delayed",
                clinicalSig: "Acute and delayed",
                freqCaucasian: "82",
                freqBlack: "89",
                freqOthers: "",
                remarks: ""
            }
        ]
    },
    colton: {
        name: "Colton System",
        code: "ISBT 015",
        class: "colton",
        antibodies: [
            {
                name: "Anti-Coᵃ",
                symbol: "CO1",
                igM: "Very rare",
                igG: "Yes",
                saline: "Yes",
                iat: "Yes",
                papain: "=",
                dosage: "Some",
                complement: "Mild to severe (rare)",
                hdfn: "No to moderate/delayed/immediate/hemolytic",
                htr: "No to moderate/delayed/immediate/hemolytic",
                clinicalSig: "No to moderate/delayed/immediate/hemolytic",
                freqCaucasian: "99.5",
                freqBlack: "99.5",
                freqOthers: "All populations: 99.5",
                remarks: ""
            },
            {
                name: "Anti-Coᵇ",
                symbol: "CO2",
                igM: "Yes",
                igG: "Yes",
                saline: "Rare",
                iat: "Yes",
                papain: "=",
                dosage: "No",
                complement: "Mild",
                hdfn: "No to moderate/delayed/hemolytic",
                htr: "No to moderate/delayed/hemolytic",
                clinicalSig: "No to moderate/delayed/hemolytic",
                freqCaucasian: "10",
                freqBlack: "10",
                freqOthers: "All populations: 10",
                remarks: ""
            }
        ]
    },
    chido: {
        name: "Chido/Rodgers System",
        code: "ISBT 017",
        class: "chido",
        antibodies: [
            {
                name: "Anti-Ch1",
                symbol: "CH/RG1",
                igM: "Yes (mostly IgG2 and IgG4)",
                igG: "Yes",
                saline: "Yes",
                iat: "Yes",
                papain: "↓",
                dosage: "No",
                complement: "No",
                hdfn: "Not hemolytic",
                htr: "Not hemolytic",
                clinicalSig: "Not hemolytic",
                freqCaucasian: "96",
                freqBlack: "96",
                freqOthers: "Most populations: 96, Japanese: 99",
                remarks: "Most anti-Ch1 are IgG2 and IgG4. A few reports describe anaphylactic transfusion reactions from plasma products."
            },
            {
                name: "Anti-Rg1",
                symbol: "CH/RG11",
                igM: "Yes",
                igG: "Yes",
                saline: "Yes",
                iat: "Yes",
                papain: "↓",
                dosage: "No",
                complement: "No",
                hdfn: "Not hemolytic",
                htr: "Not hemolytic",
                clinicalSig: "Not hemolytic",
                freqCaucasian: ">98",
                freqBlack: ">98",
                freqOthers: "All populations: >98",
                remarks: "A few reports describe anaphylactic transfusion reactions from plasma products and platelets."
            }
        ]
    },
    knops: {
        name: "Knops System",
        code: "ISBT 022",
        class: "knops",
        antibodies: [
            {
                name: "Anti-Knᵃ",
                symbol: "KN1",
                igM: "Yes",
                igG: "Yes",
                saline: "Yes",
                iat: "Yes",
                papain: "↓",
                dosage: "No",
                complement: "No",
                hdfn: "No",
                htr: "No",
                clinicalSig: "No",
                freqCaucasian: "94.5",
                freqBlack: "99.9",
                freqOthers: "",
                remarks: ""
            },
            {
                name: "Anti-McCᵃ",
                symbol: "KN3",
                igM: "Yes",
                igG: "Yes",
                saline: "Yes",
                iat: "Yes",
                papain: "↓",
                dosage: "No",
                complement: "No",
                hdfn: "No",
                htr: "No",
                clinicalSig: "No",
                freqCaucasian: "98",
                freqBlack: "94",
                freqOthers: "",
                remarks: ""
            },
            {
                name: "Anti-Ykᵃ",
                symbol: "KN5",
                igM: "Yes",
                igG: "Most",
                saline: "Yes",
                iat: "Yes",
                papain: "↓",
                dosage: "No",
                complement: "No",
                hdfn: "No",
                htr: "No",
                clinicalSig: "No",
                freqCaucasian: "92",
                freqBlack: "98",
                freqOthers: "",
                remarks: ""
            }
        ]
    },
    jmh: {
        name: "JMH System",
        code: "ISBT 026",
        class: "jmh",
        antibodies: [
            {
                name: "Anti-JMH",
                symbol: "JMH1",
                igM: "Yes",
                igG: "Yes",
                saline: "Yes",
                iat: "Yes",
                papain: "↓",
                dosage: "No",
                complement: "No",
                hdfn: "No",
                htr: "No",
                clinicalSig: "No",
                freqCaucasian: "100",
                freqBlack: "100",
                freqOthers: "All populations: 100",
                remarks: "JMH⁻ or JMH-weak phenotypes can be (transiently) acquired; anti-JMH in that case is mostly IgG4."
            }
        ]
    },
    i: {
        name: "I & Ii Systems",
        code: "ISBT 027, 207",
        class: "i",
        antibodies: [
            {
                name: "Anti-I",
                symbol: "I1",
                igM: "Yes",
                igG: "Rare",
                saline: "Yes",
                iat: "Very rare",
                papain: "↑↑",
                dosage: "No",
                complement: "Yes, some hemolytic",
                hdfn: "No",
                htr: "No",
                clinicalSig: "No",
                freqCaucasian: ">99 (Adults)",
                freqBlack: ">99 (Adults)",
                freqOthers: "Adults: >99",
                remarks: "Most common cold autoantibody, rare alloantibody in I⁻ (adult i). Associated with CHAD and Mycoplasma pneumoniae infection."
            },
            {
                name: "Anti-i",
                symbol: "I2",
                igM: "Yes",
                igG: "Rare",
                saline: "Most",
                iat: "Very rare",
                papain: "↑↑",
                dosage: "No",
                complement: "Yes, some hemolytic",
                hdfn: "Rare",
                htr: "No",
                clinicalSig: "No",
                freqCaucasian: "100",
                freqBlack: "100",
                freqOthers: "100",
                remarks: "Autoantibody can occur in serum of people with infectious mononucleosis and some lymphoproliferative disorders."
            }
        ]
    },
    jr: {
        name: "JR System",
        code: "ISBT 032",
        class: "jr",
        antibodies: [
            {
                name: "Anti-Jrᵃ",
                symbol: "JR1",
                igM: "Some",
                igG: "Yes",
                saline: "Yes",
                iat: "Yes",
                papain: "↑",
                dosage: "Yes",
                complement: "Some",
                hdfn: "Positive DAT but usually no HDFN; however one fatal case of HFDN",
                htr: "Probably",
                clinicalSig: "Probably",
                freqCaucasian: ">99",
                freqBlack: ">99",
                freqOthers: "All populations: >99",
                remarks: "The Jr(a⁻) phenotype has been found mostly in Japanese and other Asians."
            }
        ]
    },
    lan: {
        name: "LAN System",
        code: "ISBT 033",
        class: "lan",
        antibodies: [
            {
                name: "Anti-Lan",
                symbol: "LAN1",
                igM: "Yes",
                igG: "Yes",
                saline: "Some",
                iat: "Yes",
                papain: "=",
                dosage: "No",
                complement: "No to mild",
                hdfn: "No to severe/hemolytic",
                htr: "No to severe/hemolytic",
                clinicalSig: "No to severe/hemolytic",
                freqCaucasian: ">99",
                freqBlack: ">99",
                freqOthers: "All populations: >99",
                remarks: "The Lan⁻ phenotypes found in about 1 in 20,000 people; found in Blacks, Caucasians and Japanese."
            }
        ]
    },
    vel: {
        name: "VEL System",
        code: "ISBT 034",
        class: "vel",
        antibodies: [
            {
                name: "Anti-Vel",
                symbol: "VEL1",
                igM: "Yes (usually a mixture of IgM and IgG)",
                igG: "Yes (usually a mixture of IgM and IgG)",
                saline: "Yes",
                iat: "Yes",
                papain: "↑↑",
                dosage: "No",
                complement: "Yes, some hemolytic",
                hdfn: "Positive DAT to severe",
                htr: "No to severe/hemolytic",
                clinicalSig: "No to severe/hemolytic",
                freqCaucasian: ">99.9",
                freqBlack: ">99.9",
                freqOthers: "All populations: >99.9",
                remarks: "Red cells with weak Vel expression may be mistyped as Vel⁻. Vel⁻ RBCs found in 1 in ~4,000 in Norwegians and Swedes."
            }
        ]
    },
    cost: {
        name: "COST Collection",
        code: "ISBT 205",
        class: "cost",
        antibodies: [
            {
                name: "Anti-Csᵃ",
                symbol: "COST1",
                igM: "Yes",
                igG: "Yes",
                saline: "Yes",
                iat: "Yes",
                papain: "=",
                dosage: "No",
                complement: "No",
                hdfn: "No",
                htr: "No",
                clinicalSig: "No",
                freqCaucasian: ">98",
                freqBlack: "95",
                freqOthers: "Most populations: >98",
                remarks: ""
            },
            {
                name: "Anti-Csᵇ",
                symbol: "COST2",
                igM: "Yes",
                igG: "Yes",
                saline: "Yes",
                iat: "Yes",
                papain: "=",
                dosage: "No",
                complement: "",
                hdfn: "",
                htr: "",
                clinicalSig: "",
                freqCaucasian: "34",
                freqBlack: "34",
                freqOthers: "Most populations: 34",
                remarks: "Only one example of antibody is published."
            }
        ]
    }
};

let currentFilter = { system: 'all', clinical: 'all' };

// Initialize the app
function init() {
    renderSystems();
    setupEventListeners();
}

function setupEventListeners() {
    document.getElementById('searchInput').addEventListener('input', handleSearch);
    document.getElementById('filterSystem').addEventListener('change', handleFilterChange);
    document.getElementById('filterClinical').addEventListener('change', handleClinicalFilterChange);
}

function renderSystems() {
    const grid = document.getElementById('systemsGrid');
    grid.innerHTML = '';

    Object.keys(bloodGroupData).forEach(key => {
        const system = bloodGroupData[key];
        if (shouldShowSystem(system, key)) {
            const card = createSystemCard(system, key);
            grid.appendChild(card);
        }
    });
}

function shouldShowSystem(system, key) {
    // System filter
    if (currentFilter.system !== 'all') {
        if (currentFilter.system === 'other') {
            const majorSystems = ['abo', 'rh', 'kell', 'duffy', 'kidd', 'mns', 'lewis', 'h'];
            if (majorSystems.includes(key)) return false;
        } else if (key !== currentFilter.system && system.class !== currentFilter.system) {
            return false;
        }
    }

    // Clinical filter
    if (currentFilter.clinical !== 'all') {
        const hasRelevantAntibody = system.antibodies.some(ab => {
            if (currentFilter.clinical === 'hdfn') {
                return ab.hdfn && ab.hdfn !== 'No' && ab.hdfn !== 'Rare';
            } else if (currentFilter.clinical === 'htr') {
                return ab.htr && ab.htr !== 'No' && !ab.htr.startsWith('No to');
            } else if (currentFilter.clinical === 'hemolytic') {
                return ab.complement && ab.complement.includes('hemolytic');
            }
            return false;
        });
        if (!hasRelevantAntibody) return false;
    }

    return true;
}

function createSystemCard(system, key) {
    const card = document.createElement('div');
    card.className = `system-card ${system.class}`;
    card.innerHTML = `
        <div class="system-header">
            <div class="system-name">${system.name}</div>
            <div class="system-code">${system.code}</div>
        </div>
        <div style="color: #666; margin-bottom: 1rem;">
            ${system.antibodies.length} antibodies
        </div>
        <div style="font-size: 1.5rem; text-align: center; color: #999;">▼</div>
        <div class="antibody-list" id="list-${key}">
            ${system.antibodies.map(ab => createAntibodyItem(ab, system.class)).join('')}
        </div>
    `;

    card.addEventListener('click', (e) => {
        if (!e.target.closest('.antibody-item')) {
            toggleAntibodyList(key, card);
        }
    });

    return card;
}

function toggleAntibodyList(key, card) {
    const list = document.getElementById(`list-${key}`);
    const isExpanded = list.style.display === 'block';

    list.style.display = isExpanded ? 'none' : 'block';
    card.classList.toggle('expanded');
}

function createAntibodyItem(antibody, systemClass) {
    return `
        <div class="antibody-item" onclick="showAntibodyDetail(event, '${antibody.symbol}')">
            <div class="antibody-name">${antibody.name}</div>
            <div class="antibody-props">
                <div class="prop">
                    <span class="prop-label">IgG:</span>
                    <span class="${getBadgeClass(antibody.igG)}">${antibody.igG}</span>
                </div>
                <div class="prop">
                    <span class="prop-label">IgM:</span>
                    <span class="${getBadgeClass(antibody.igM)}">${antibody.igM}</span>
                </div>
                <div class="prop">
                    <span class="prop-label">HDFN:</span>
                    <span class="${getClinicalBadgeClass(antibody.hdfn)}">${truncate(antibody.hdfn, 15)}</span>
                </div>
                <div class="prop">
                    <span class="prop-label">HTR:</span>
                    <span class="${getClinicalBadgeClass(antibody.htr)}">${truncate(antibody.htr, 15)}</span>
                </div>
            </div>
        </div>
    `;
}

function getBadgeClass(value) {
    if (!value) return 'badge';
    const lower = value.toLowerCase();
    if (lower === 'yes' || lower === 'most') return 'badge yes';
    if (lower === 'no') return 'badge no';
    if (lower === 'rare' || lower === 'some' || lower === 'very rare') return 'badge rare';
    return 'badge some';
}

function getClinicalBadgeClass(value) {
    if (!value) return 'badge';
    const lower = value.toLowerCase();
    if (lower === 'no' || lower.startsWith('no ')) return 'badge no';
    if (lower.includes('severe') || lower.includes('hemolytic')) return 'badge yes';
    if (lower.includes('mild') || lower.includes('moderate')) return 'badge rare';
    return 'badge some';
}

function truncate(str, length) {
    if (!str) return '';
    return str.length > length ? str.substring(0, length) + '...' : str;
}

function showAntibodyDetail(event, symbol) {
    event.stopPropagation();

    // Find the antibody
    let antibody = null;
    let systemName = '';

    for (const key in bloodGroupData) {
        const system = bloodGroupData[key];
        const found = system.antibodies.find(ab => ab.symbol === symbol);
        if (found) {
            antibody = found;
            systemName = system.name;
            break;
        }
    }

    if (!antibody) return;

    const modalBody = document.getElementById('modalBody');
    modalBody.innerHTML = `
        <div class="modal-header">
            <h2 class="modal-title">${antibody.name}</h2>
            <p class="modal-subtitle">${systemName} • ${antibody.symbol}</p>
        </div>

        <div class="frequency-section">
            <div class="frequency-title">Antigen Frequency (%)</div>
            <div class="frequency-grid">
                <div class="frequency-item">
                    <strong>Caucasian:</strong> ${antibody.freqCaucasian || 'N/A'}%
                </div>
                <div class="frequency-item">
                    <strong>Black:</strong> ${antibody.freqBlack || 'N/A'}%
                </div>
                ${antibody.freqOthers ? `
                <div class="frequency-item" style="grid-column: 1 / -1;">
                    <strong>Other Populations:</strong> ${antibody.freqOthers}
                </div>
                ` : ''}
            </div>
        </div>

        <div class="detail-grid">
            <div class="detail-item">
                <div class="detail-label">Immunoglobulin Class</div>
                <div class="detail-value">
                    <div><strong>IgM:</strong> ${antibody.igM}</div>
                    <div><strong>IgG:</strong> ${antibody.igG}</div>
                </div>
            </div>

            <div class="detail-item">
                <div class="detail-label">In Vitro Characteristics</div>
                <div class="detail-value">
                    <div><strong>Saline (RT):</strong> ${antibody.saline}</div>
                    <div><strong>IAT:</strong> ${antibody.iat}</div>
                    <div><strong>Papain (37°C):</strong> ${antibody.papain}</div>
                </div>
            </div>

            <div class="detail-item">
                <div class="detail-label">Dosage & Complement</div>
                <div class="detail-value">
                    <div><strong>Dosage:</strong> ${antibody.dosage}</div>
                    <div><strong>Complement:</strong> ${antibody.complement}</div>
                </div>
            </div>

            <div class="detail-item">
                <div class="detail-label">Clinical Significance</div>
                <div class="detail-value">
                    <div><strong>HDFN:</strong> ${antibody.hdfn}</div>
                    <div><strong>HTR:</strong> ${antibody.htr}</div>
                    <div><strong>Overall:</strong> ${antibody.clinicalSig}</div>
                </div>
            </div>
        </div>

        ${antibody.remarks ? `
        <div class="remarks-section">
            <div class="remarks-title">⚠️ Clinical Notes & Remarks</div>
            <div>${antibody.remarks}</div>
        </div>
        ` : ''}
    `;

    document.getElementById('antibodyModal').style.display = 'block';
}

function closeModal() {
    document.getElementById('antibodyModal').style.display = 'none';
}

function handleSearch(e) {
    const query = e.target.value.toLowerCase();

    if (query.length === 0) {
        renderSystems();
        return;
    }

    const grid = document.getElementById('systemsGrid');
    grid.innerHTML = '';

    Object.keys(bloodGroupData).forEach(key => {
        const system = bloodGroupData[key];
        const matchingAntibodies = system.antibodies.filter(ab =>
            ab.name.toLowerCase().includes(query) ||
            ab.symbol.toLowerCase().includes(query) ||
            system.name.toLowerCase().includes(query) ||
            (ab.remarks && ab.remarks.toLowerCase().includes(query))
        );

        if (matchingAntibodies.length > 0 && shouldShowSystem(system, key)) {
            const filteredSystem = { ...system, antibodies: matchingAntibodies };
            const card = createSystemCard(filteredSystem, key);
            grid.appendChild(card);

            // Auto-expand if searching
            const list = card.querySelector('.antibody-list');
            list.style.display = 'block';
            card.classList.add('expanded');
        }
    });

    if (grid.children.length === 0) {
        grid.innerHTML = '<div style="text-align: center; padding: 3rem; color: #999; grid-column: 1 / -1;"><h3>No results found</h3><p>Try a different search term</p></div>';
    }
}

function handleFilterChange(e) {
    currentFilter.system = e.target.value;
    renderSystems();
}

function handleClinicalFilterChange(e) {
    currentFilter.clinical = e.target.value;
    renderSystems();
}

// Close modal when clicking outside
window.onclick = function(event) {
    const modal = document.getElementById('antibodyModal');
    if (event.target === modal) {
        closeModal();
    }
}

// Initialize on load
document.addEventListener('DOMContentLoaded', init);
