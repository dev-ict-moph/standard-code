# Standard Code
การตั้งชื่อไฟล์และชื่อฟิลด์ อ้างอิงจาก MongoDB Naming Standards and Guidelines

- MongoDB Collection Naming => Lower case Example: account_record, credit_history


- [Links](https://www.thecodebuzz.com/mongo-db-naming-conventions-standards-guidelines/#aioseo-mongomongodb-naming-standards-and-guidelines---database-naming)

---
## คำนำหน้าชื่อ -- title_codes.csv

#### แหล่งมาตรฐานข้อมูล 

- [มหาดไทย](http://edw-opendata.moi.go.th/dataset/page/5f11b90b2ef969d0f4f4594c10086ebe0229688d38c9d)

##### ตัวอย่าง
| TitleCode | TitleNameTh | TitleNameEn |
| :-------: | :---------: | :---------: |
| 003       | นาย	      | MR.         |
| 004	    | นางสาว      | MISS        |

---
## หมู่เลือด -- blood_groups.csv 

#### แหล่งมาตรฐานข้อมูล 

- [43แฟ้ม](https://drive.google.com/file/d/1i9JC_r5LDbXqBZGGf1kyoRqR3E7CSUyW/view)

###### ฟิล์ดข้อมูลที่ใช้แสดงผลเป็นหลัก :triangular_flag_on_post: 

##### ตัวอย่าง
| BloodGroupCode | 	BloodGroupNameTh | BloodGroupNameEn :triangular_flag_on_post: |
| :------------: | :---------------: | :--------------: |
| 1              | เอ                 | A                |

---
## หมู่เลือดRH -- rh_blood_groups.csv 

#### แหล่งมาตรฐานข้อมูล 

- [43แฟ้ม](https://drive.google.com/file/d/11MkFMS-4cVaNTbBXQmjRJ8_VX82JoUyM/view)

##### ตัวอย่าง
| RhBloodGroupCode | RhBloodGroupNameTh | RhBloodGroupnameEn |
| :--------------: | :----------------: | :----------------: |
| 1                |                    | Positive           |
| 2                |                    | Negative           |

---
## เพศ -- genders.csv 

#### แหล่งมาตรฐานข้อมูล

- [มหาดไทย+](https://data.go.th/dataset/view_gender)

##### ตัวอย่าง
| GenderCode | GenderNameTh | GenderNameEn |
| :--------: | :----------: | :----------: |
| 1          | ชาย          | Male         |

---
## สัญชาติ -- nationalities.csv 

#### แหล่งมาตรฐานข้อมูล

- [มหาดไทย](http://edw-opendata.moi.go.th/dataset/page/5f11bb7058296d0cd0a5609c9637cd33da403d6d02afa)

##### ตัวอย่าง
| NationalityCode | NationalityNameTh | NationalityNameEn |
| :--------: | :----------: | :----------: |
| 002          | โปรตุเกส          | PORTUGUESE         |

---


## สถานภาพสมรส -- marital_status.csv 

#### แหล่งมาตรฐานข้อมูล 

- [มหาดไทย](http://edw-opendata.moi.go.th/dataset/page/5efea934a63f8b7dc320999b9a314ce67d9691321b627)

##### ตัวอย่าง
| MaritalStatusCode | MaritalStatusNameTh | MaritalStatusNameEn |
| :---------: | :------------: | :------------: |
| 1           | โสด            | Single         |
| 2           | สมรส           | Married        |

---
## อาชีพ -- occupations.csv 

#### แหล่งมาตรฐานข้อมูล 

- [43แฟ้ม](https://drive.google.com/file/d/1fu9ql1pjVfbKqmIJlM8ZZsCO5RsQfR0f/view)

##### ตัวอย่าง
| OccupationCode | OccupationNameTh | OccupationNameEn |
| :------------: | :--------------: | :--------------: |
| 0110           | ทหารชั้นสัญญาบัตร  |                   |
| 0210           | ทหารชั้นประทวน    |                   |

---
## ประเภทการวินิจฉัย -- diagnosis_types.csv 

#### แหล่งมาตรฐานข้อมูล 

- [43แฟ้ม](https://drive.google.com/open?id=1o7QU9sNAacfRPpKsG0S1zgVhLOLLdsTk)

##### ตัวอย่าง
| DiagnosisTypesCode | DiagnosisTypesNameTh | DiagnosisTypesNameEn |
| :----------------: | :------------------: | :------------------: |
| 1	                 | การวินิจฉัยโรคหลัก       | PRINCIPLE DX         |
| 2	                 | การวินิจฉัยโรคร่วม        | CO-MORBIDITY         |

---
## การวินิจฉัยโรคและอาการ (ICD 10 TM) -- diagnosis.csv 

#### แหล่งมาตรฐานข้อมูล 

- [43แฟ้ม](https://drive.google.com/file/d/1gBnNQY8Tbw60rlAUY4IslDp31XQjGjms/view?usp=sharing)


##### ตัวอย่าง
| DiagnosisCode | DiagnosisNameTh | DiagnosisNameEn |
| :----------------: | :------------------: | :------------------: |
| A000	             | อหิวาตกโรคจากเชื้อ วิบริโอ คอเลเรโอ 1 ไบอาวาร์ คอเลเร | Cholera due to Vibrio cholerae 01, biovar cholerae         |
| A001	             | อหิวาตกโรคจากเชื้อ วิบริโอ คอเลเรโอ 1 ไบอาวาร์ เอลทอร์ | Cholera due to Vibrio cholerae 01, biovar eltor         |

---
## สิทธิการรักษาพยาบาล -- rights.csv  

#### แหล่งมาตรฐานข้อมูล 

- [สปสช.](https://www.nhso.go.th/downloads/64)
- [43แฟ้ม](https://drive.google.com/file/d/13HROCTleOTD6uq_Tk4AGG6eiqHzOAnVZ/view)

##### ตัวอย่าง
| RightsCode |  RightsNameTh |  RightsNameEn  |
| :---------: | :----------: | :-----------: |
| SSS	      | สิทธิประกันสังคม | Social Security Scheme|
| UCS         | สิทธิหลักประกันสุขภาพ | Universal Coverage Scheme |

---
## สถานพยาบาล -- hosp_names.csv

#### แหล่งมาตรฐานข้อมูล 

- [กยผ.](http://203.157.10.8/hcode_2020/p_export.php)

##### ตัวอย่าง
| HospCode |  HospNameTh             |  HospNameEn | HospProvinceCode | HospProvinceNameTh | HospProvinceNameEn | HospZone |
| :------: | :----------:            | :---------: | :--------------: | :----------------: | :----------------: | :------: |
| 41866	   | คลินิกการแพทย์แผนไทยเตาปูน |             | 10               | กรุงเทพมหานคร      | Bangkok             | 13      |

---
## แผนกวินิจฉัย -- main_departments.csv

#### แหล่งมาตรฐานข้อมูล 

- [43แฟ้ม](https://docs.google.com/spreadsheets/d/1J7HWIyReeHArOmMdPPSok_HkUzNSiTZ-/edit#gid=1692007087)

##### ตัวอย่าง
| MainDepartmentOPDCode | MainDepartmentIPDCode |  MainDepartmentNameTh | MainDepartmentNameEn | 
| :-------------------: | :-------------------: | :-------------------: | :------------------: |
| 00100	                | 10100                 |  อายุรกรรม              |                      |
| 00200	                | 10200                 |  ศัลยกรรม              |                      |

---
## ยา(43แฟ้ม) -- drugs_43_folders.csv

#### แหล่งมาตรฐานข้อมูล 

- [43แฟ้ม](https://drive.google.com/file/d/1qMrhZAqnqH-8EMIHQqxuX5zCtY5bJqhP/view)


##### ตัวอย่าง
| DrugCode | Drug24Code | ActiveIngredient | TradeName | Manufacturer | FSN |	DrugTypeCode |
|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
| | 100188000004293220181296 |	TETRACYCLINE 250 MG CAPSULE	| ACNICIN T1 CAPSULE | บริษัท อาร์ พี ซี อินเตอร์เนชั่นแนล จำกัด | ACNICIN T1 CAPSULE(บริษัท อาร์ พี ซี อินเตอร์เนชั่นแนล จำกัด)(TETRACYCLINE 250 MG CAPSULE)() |	43folders |

---
## ยา(TMT) -- tmt_drugs.csv.csv

#### แหล่งมาตรฐานข้อมูล 

- [บัญชีข้อมูลยาและรหัสยามาตรฐานไทยสำหรับยาแผนไทย](https://www.this.or.th/service/ttmt/)

- [บัญชีข้อมูลยาและรหัสยามาตรฐานไทย(TMT)](https://www.this.or.th/service/tmt/download/)


##### ตัวอย่าง
| DrugCode | Drug24Code | ActiveIngredient | Strength | DosageForm	| ContentValue | ContentUnit| DispensingUnit | TradeName | Manufacturer | FSN |	DrugTypeCode |
|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 9099264 | 420000000110000021510662 | กษัยเส้น |	|ยาลูกกลอน | |	| |					โรงพยาบาลชลบุรี |(โรงพยาบาลชลบุรี)(กษัยเส้น)()ยาลูกกลอน | TTMT |
| 105474 |                           | pantoprazole | 40 mg | gastro-resistant tablet |	 |  | tablet | CONTROLOC | ALTANA PHARMA, GERMANY |	CONTROLOC (ALTANA PHARMA, GERMANY) (pantoprazole 40 mg) gastro-resistant tablet, 1 tablet (TPU) | TMT |


