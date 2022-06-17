# Installation
**1. GTASA_AML**

1. Required ` Gta Sa Aml Apk `
2. Download ` libINISM.so `
3. Copy ` libIniSM.so ` to Path `Android/data/..gtasa../mods/*here*`


**2. Sanny Builder Compiler**

1. Download ` Opcode.txt , SASCM.INI `
2. Copy Download File to `...\Sanny Builder 3\data\sa_mobile\*here*` **<--Replace**

# How to Use?

Sanny Builder Select Game  **`[sa_mobile]`**


#### --> sm.ini
`[SECTION]`

`Int=1`

`float=2.0`

`String="This is String"`

##### 1. 0AF0 Read  INT
`0AF0: 1@ = read_int_from_ini "sm.ini" section "section" key "Int"`

##### 2. 0AF1 Write INT
`0AF1: write_int 1@ to_ini_file "sm.ini" section "section" key "Int"`

##### 3. 0AF2 Read  FLOAT
`0AF2: 1@ = read_float_from_ini "sm.ini"  section "section" key "Int"`

##### 4. 0AF3 Write FLOAT
`0AF3: write_float 1@ to_ini_file "sm.ini"  section "section" key "Int"`

##### 5. 0AF4 Read  STRING
`0AF4: 1@ = read_string_from_ini "sm.ini" section "section" key "Int"`

##### 6. 0AF5 Write STRING
`0AF5: write_string 1@ to_ini_file "sm.ini"  section "section" key "Int"`
