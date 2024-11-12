{\rtf1\ansi\ansicpg1252\cocoartf2818
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\froman\fcharset0 Times-Bold;\f1\froman\fcharset0 Times-Roman;}
{\colortbl;\red255\green255\blue255;\red0\green0\blue0;\red109\green109\blue109;}
{\*\expandedcolortbl;;\cssrgb\c0\c0\c0;\cssrgb\c50196\c50196\c50196;}
{\*\listtable{\list\listtemplateid1\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid1\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid1}
{\list\listtemplateid2\listhybrid{\listlevel\levelnfc0\levelnfcn0\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{decimal\}}{\leveltext\leveltemplateid101\'01\'00;}{\levelnumbers\'01;}\fi-360\li720\lin720 }{\listname ;}\listid2}
{\list\listtemplateid3\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid201\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid3}
{\list\listtemplateid4\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid301\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid4}}
{\*\listoverridetable{\listoverride\listid1\listoverridecount0\ls1}{\listoverride\listid2\listoverridecount0\ls2}{\listoverride\listid3\listoverridecount0\ls3}{\listoverride\listid4\listoverridecount0\ls4}}
\margl1440\margr1440\vieww17900\viewh8400\viewkind0
\deftab720
\pard\pardeftab720\sa321\partightenfactor0

\f0\b\fs48 \cf0 \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 README: Synthetic Orders Dataset for Logistics Group Delivery\
\pard\pardeftab720\sa298\partightenfactor0

\fs36 \cf0 Overview\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 This dataset represents orders for a logistics system designed to optimize batch deliveries using a group order model. The dataset includes orders from three areas in Metro Manila: 
\f0\b Makati
\f1\b0 , 
\f0\b Quezon City
\f1\b0 , and 
\f0\b Taguig
\f1\b0 , each divided into three sub-groups (A, B, and C). The goal is to simulate how products are grouped to fill up cargo space efficiently and enable users to progress through discount levels based on the quantity and dimensions of the products.\
\pard\pardeftab720\sa280\partightenfactor0

\f0\b\fs28 \cf0 Key Features:\
\pard\tx220\tx720\pardeftab720\li720\fi-720\partightenfactor0
\ls1\ilvl0
\fs24 \cf0 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Area & Sub-group
\f1\b0 : The location of the delivery, with each area (Makati, Quezon City, Taguig) divided into three sub-groups (e.g., Makati A, Makati B, Makati C).\
\ls1\ilvl0
\f0\b \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Product
\f1\b0 : A unique identifier for the product (e.g., Product-1, Product-2, etc.).\
\ls1\ilvl0
\f0\b \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Product Price
\f1\b0 : The price of the product in PHP.\
\ls1\ilvl0
\f0\b \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Order Time
\f1\b0 : The timestamp when the order was placed.\
\ls1\ilvl0
\f0\b \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Dimensions
\f1\b0 : The physical attributes of the product (length, width, height in centimeters, and weight in kilograms).\
\pard\pardeftab720\sa298\partightenfactor0

\f0\b\fs36 \cf0 Dataset Columns:\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa240\partightenfactor0
\ls2\ilvl0
\fs24 \cf0 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	1	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Area & Sub-group
\f1\b0 : The area and corresponding sub-group for each order. This field is a combination of the area (Makati, Quezon City, Taguig) and one of its sub-groups (A, B, or C).\uc0\u8232 Example: "Makati A", "Taguig B", "Quezon City C".\
\ls2\ilvl0
\f0\b \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	2	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Product
\f1\b0 : A unique product identifier, such as "Product-1", "Product-2", etc.\
\ls2\ilvl0
\f0\b \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	3	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Product Price
\f1\b0 : The price of the product in Philippine Peso (PHP), randomly generated within a range of 100 to 500 PHP.\
\ls2\ilvl0
\f0\b \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	4	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Order Time
\f1\b0 : The timestamp when the order was placed, randomly assigned to a date within the past 30 days.\
\ls2\ilvl0
\f0\b \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	5	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Length (cm)
\f1\b0 : The length of the product in centimeters, randomly generated within the range of 5 to 50 cm.\
\ls2\ilvl0
\f0\b \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	6	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Width (cm)
\f1\b0 : The width of the product in centimeters, randomly generated within the range of 5 to 50 cm.\
\ls2\ilvl0
\f0\b \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	7	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Height (cm)
\f1\b0 : The height of the product in centimeters, randomly generated within the range of 5 to 50 cm.\
\ls2\ilvl0
\f0\b \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	8	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Weight (kg)
\f1\b0 : The weight of the product in kilograms, randomly generated between 0.5 kg and 10 kg.\
\pard\pardeftab720\sa298\partightenfactor0

\f0\b\fs36 \cf0 Usage\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 This dataset is ideal for testing logistics systems that need to optimize group deliveries by tracking product dimensions and allowing users to jump between sub-groups within areas to speed up the discount process.\
\pard\pardeftab720\sa280\partightenfactor0

\f0\b\fs28 \cf0 Example Use Cases:\
\pard\tx220\tx720\pardeftab720\li720\fi-720\partightenfactor0
\ls3\ilvl0
\fs24 \cf0 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Testing group order logistics
\f1\b0 : Simulate how products are grouped based on area and dimensions to maximize truck space.\
\ls3\ilvl0
\f0\b \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Discount system validation
\f1\b0 : Use the product dimensions and area/sub-group assignments to calculate how discount levels progress based on the size and number of products added.\
\pard\pardeftab720\sa298\partightenfactor0

\f0\b\fs36 \cf0 Data Format\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 The dataset is provided in CSV format and contains the following columns:\

\itap1\trowd \taflags0 \trgaph108\trleft-108 \trbrdrt\brdrnil \trbrdrl\brdrnil \trbrdrr\brdrnil 
\clvertalc \clshdrawnil \clwWidth1911\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx1080
\clvertalc \clshdrawnil \clwWidth946\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx2160
\clvertalc \clshdrawnil \clwWidth1415\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx3240
\clvertalc \clshdrawnil \clwWidth1224\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx4320
\clvertalc \clshdrawnil \clwWidth1260\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx5400
\clvertalc \clshdrawnil \clwWidth1175\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx6480
\clvertalc \clshdrawnil \clwWidth1220\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx7560
\clvertalc \clshdrawnil \clwWidth1206\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx8640
\pard\intbl\itap1\pardeftab720\qc\partightenfactor0

\f0\b \cf0 Area & Sub-group\cell 
\pard\intbl\itap1\pardeftab720\qc\partightenfactor0
\cf0 Product\cell 
\pard\intbl\itap1\pardeftab720\qc\partightenfactor0
\cf0 Product Price\cell 
\pard\intbl\itap1\pardeftab720\qc\partightenfactor0
\cf0 Order Time\cell 
\pard\intbl\itap1\pardeftab720\qc\partightenfactor0
\cf0 Length (cm)\cell 
\pard\intbl\itap1\pardeftab720\qc\partightenfactor0
\cf0 Width (cm)\cell 
\pard\intbl\itap1\pardeftab720\qc\partightenfactor0
\cf0 Height (cm)\cell 
\pard\intbl\itap1\pardeftab720\qc\partightenfactor0
\cf0 Weight (kg)\cell \row

\itap1\trowd \taflags0 \trgaph108\trleft-108 \trbrdrl\brdrnil \trbrdrr\brdrnil 
\clvertalc \clshdrawnil \clwWidth1911\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx1080
\clvertalc \clshdrawnil \clwWidth946\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx2160
\clvertalc \clshdrawnil \clwWidth1415\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx3240
\clvertalc \clshdrawnil \clwWidth1224\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx4320
\clvertalc \clshdrawnil \clwWidth1260\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx5400
\clvertalc \clshdrawnil \clwWidth1175\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx6480
\clvertalc \clshdrawnil \clwWidth1220\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx7560
\clvertalc \clshdrawnil \clwWidth1206\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx8640
\pard\intbl\itap1\pardeftab720\partightenfactor0

\f1\b0 \cf0 Makati A\cell 
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf0 Product-1\cell 
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf0 200.50\cell 
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf0 2024-11-01\cell 
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf0 20.3\cell 
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf0 10.5\cell 
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf0 5.7\cell 
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf0 2.3\cell \row

\itap1\trowd \taflags0 \trgaph108\trleft-108 \trbrdrl\brdrnil \trbrdrr\brdrnil 
\clvertalc \clshdrawnil \clwWidth1911\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx1080
\clvertalc \clshdrawnil \clwWidth946\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx2160
\clvertalc \clshdrawnil \clwWidth1415\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx3240
\clvertalc \clshdrawnil \clwWidth1224\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx4320
\clvertalc \clshdrawnil \clwWidth1260\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx5400
\clvertalc \clshdrawnil \clwWidth1175\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx6480
\clvertalc \clshdrawnil \clwWidth1220\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx7560
\clvertalc \clshdrawnil \clwWidth1206\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx8640
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf0 Taguig B\cell 
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf0 Product-2\cell 
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf0 150.75\cell 
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf0 2024-10-25\cell 
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf0 30.4\cell 
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf0 12.1\cell 
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf0 9.2\cell 
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf0 3.5\cell \row

\itap1\trowd \taflags0 \trgaph108\trleft-108 \trbrdrl\brdrnil \trbrdrr\brdrnil 
\clvertalc \clshdrawnil \clwWidth1911\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx1080
\clvertalc \clshdrawnil \clwWidth946\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx2160
\clvertalc \clshdrawnil \clwWidth1415\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx3240
\clvertalc \clshdrawnil \clwWidth1224\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx4320
\clvertalc \clshdrawnil \clwWidth1260\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx5400
\clvertalc \clshdrawnil \clwWidth1175\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx6480
\clvertalc \clshdrawnil \clwWidth1220\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx7560
\clvertalc \clshdrawnil \clwWidth1206\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx8640
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf0 Quezon City C\cell 
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf0 Product-3\cell 
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf0 300.00\cell 
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf0 2024-10-18\cell 
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf0 15.7\cell 
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf0 14.8\cell 
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf0 10.0\cell 
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf0 4.2\cell \row

\itap1\trowd \taflags0 \trgaph108\trleft-108 \trbrdrl\brdrnil \trbrdrt\brdrnil \trbrdrr\brdrnil 
\clvertalc \clshdrawnil \clwWidth1911\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx1080
\clvertalc \clshdrawnil \clwWidth946\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx2160
\clvertalc \clshdrawnil \clwWidth1415\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx3240
\clvertalc \clshdrawnil \clwWidth1224\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx4320
\clvertalc \clshdrawnil \clwWidth1260\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx5400
\clvertalc \clshdrawnil \clwWidth1175\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx6480
\clvertalc \clshdrawnil \clwWidth1220\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx7560
\clvertalc \clshdrawnil \clwWidth1206\clftsWidth3 \clmart10 \clmarl10 \clmarb10 \clmarr10 \clbrdrt\brdrnil \clbrdrl\brdrnil \clbrdrb\brdrnil \clbrdrr\brdrnil \clpadt20 \clpadl20 \clpadb20 \clpadr20 \gaph\cellx8640
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf0 ...\cell 
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf0 ...\cell 
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf0 ...\cell 
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf0 ...\cell 
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf0 ...\cell 
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf0 ...\cell 
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf0 ...\cell 
\pard\intbl\itap1\pardeftab720\partightenfactor0
\cf0 ...\cell \lastrow\row
\pard\pardeftab720\sa298\partightenfactor0

\f0\b\fs36 \cf0 How to Use\
\pard\tx220\tx720\pardeftab720\li720\fi-720\partightenfactor0
\ls4\ilvl0
\fs24 \cf0 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Data Analysis
\f1\b0 : Load the dataset into a data analysis tool (e.g., Pandas in Python) to analyze the distribution of orders across areas, sub-groups, and product dimensions.\
\ls4\ilvl0
\f0\b \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Logistics Optimization
\f1\b0 : Use the product dimensions and area/sub-group data to model logistics optimization problems, such as grouping products to maximize cargo space and track discount progress.\
\pard\pardeftab720\sa298\partightenfactor0

\f0\b\fs36 \cf0 License\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 This dataset is synthetic and intended for testing and simulation purposes. There are no usage restrictions, but it should not be used for commercial purposes without further modification.\
}