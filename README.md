# All-India-Pincode-Directory

### SQL Format ###
~~~sql
DROP TABLE allindiapincode;
CREATE TABLE allindiapincode (officename varchar(50), pincode bigint, officeType varchar(50), Deliverystatus varchar(50), divisionname varchar(50), regionname varchar(50), circlename varchar(50), Taluk varchar(50), Districtname varchar(50), statename varchar(50), Telephone varchar(50), relatedSuboffice varchar(50), relatedHeadoffice varchar(50)) ENGINE=MyISAM DEFAULT CHARSET=latin1;
INSERT INTO allindiapincode (officename, pincode, officeType, Deliverystatus, divisionname, regionname, circlename, Taluk, Districtname, statename, Telephone, relatedSuboffice, relatedHeadoffice) VALUES ('Achalapur B.O', 504273, 'B.O', 'Delivery', 'Adilabad', 'Hyderabad', 'Andhra Pradesh', 'Asifabad', 'Adilabad', 'TELANGANA', 'NA', 'Rechini S.O', 'Mancherial H.O');
INSERT INTO allindiapincode (officename, pincode, officeType, Deliverystatus, divisionname, regionname, circlename, Taluk, Districtname, statename, Telephone, relatedSuboffice, relatedHeadoffice) VALUES ('Ada B.O', 504293, 'B.O', 'Delivery', 'Adilabad', 'Hyderabad', 'Andhra Pradesh', 'Asifabad', 'Adilabad', 'TELANGANA', 'NA', 'Asifabad S.O', 'Mancherial H.O');
~~~

### JSON Format ###
~~~json
[
  {
    "officename": "Achalapur B.O",
    "pincode": 504273,
    "officeType": "B.O",
    "Deliverystatus": "Delivery",
    "divisionname": "Adilabad",
    "regionname": "Hyderabad",
    "circlename": "Andhra Pradesh",
    "Taluk": "Asifabad",
    "Districtname": "Adilabad",
    "statename": "TELANGANA",
    "Telephone": "NA",
    "relatedSuboffice": "Rechini S.O",
    "relatedHeadoffice": "Mancherial H.O"
  },
  {
    "officename": "Ada B.O",
    "pincode": 504293,
    "officeType": "B.O",
    "Deliverystatus": "Delivery",
    "divisionname": "Adilabad",
    "regionname": "Hyderabad",
    "circlename": "Andhra Pradesh",
    "Taluk": "Asifabad",
    "Districtname": "Adilabad",
    "statename": "TELANGANA",
    "Telephone": "NA",
    "relatedSuboffice": "Asifabad S.O",
    "relatedHeadoffice": "Mancherial H.O"
  },
  {
    // ... all other datas
  }
]
~~~

### XML Format ###
~~~xml
<?xml version="1.0" encoding="Cp1252"?>

<TABLE>
 <CATALOG>
  pincode
 </CATALOG>
 <NAME>
  allindiapincode
 </NAME>
 <COLUMNS>
  <COLUMN>
   <NAME>
    officename
   </NAME>
   <DATA_TYPE>
    varchar(50)
   </DATA_TYPE>
   <NULLABLE/>
   <COMMENT>
    
   </COMMENT>
  </COLUMN>
  <COLUMN>
   <NAME>
    pincode
   </NAME>
   <DATA_TYPE>
    bigint
   </DATA_TYPE>
   <NULLABLE/>
   <COMMENT>
    
   </COMMENT>
  </COLUMN>
  <COLUMN>
   <NAME>
    officeType
   </NAME>
   <DATA_TYPE>
    varchar(50)
   </DATA_TYPE>
   <NULLABLE/>
   <COMMENT>
    
   </COMMENT>
  </COLUMN>
  <COLUMN>
   <NAME>
    Deliverystatus
   </NAME>
   <DATA_TYPE>
    varchar(50)
   </DATA_TYPE>
   <NULLABLE/>
   <COMMENT>
    
   </COMMENT>
  </COLUMN>
  <COLUMN>
   <NAME>
    divisionname
   </NAME>
   <DATA_TYPE>
    varchar(50)
   </DATA_TYPE>
   <NULLABLE/>
   <COMMENT>
    
   </COMMENT>
  </COLUMN>
  <COLUMN>
   <NAME>
    regionname
   </NAME>
   <DATA_TYPE>
    varchar(50)
   </DATA_TYPE>
   <NULLABLE/>
   <COMMENT>
    
   </COMMENT>
  </COLUMN>
  <COLUMN>
   <NAME>
    circlename
   </NAME>
   <DATA_TYPE>
    varchar(50)
   </DATA_TYPE>
   <NULLABLE/>
   <COMMENT>
    
   </COMMENT>
  </COLUMN>
  <COLUMN>
   <NAME>
    Taluk
   </NAME>
   <DATA_TYPE>
    varchar(50)
   </DATA_TYPE>
   <NULLABLE/>
   <COMMENT>
    
   </COMMENT>
  </COLUMN>
  <COLUMN>
   <NAME>
    Districtname
   </NAME>
   <DATA_TYPE>
    varchar(50)
   </DATA_TYPE>
   <NULLABLE/>
   <COMMENT>
    
   </COMMENT>
  </COLUMN>
  <COLUMN>
   <NAME>
    statename
   </NAME>
   <DATA_TYPE>
    varchar(50)
   </DATA_TYPE>
   <NULLABLE/>
   <COMMENT>
    
   </COMMENT>
  </COLUMN>
  <COLUMN>
   <NAME>
    Telephone
   </NAME>
   <DATA_TYPE>
    varchar(50)
   </DATA_TYPE>
   <NULLABLE/>
   <COMMENT>
    
   </COMMENT>
  </COLUMN>
  <COLUMN>
   <NAME>
    relatedSuboffice
   </NAME>
   <DATA_TYPE>
    varchar(50)
   </DATA_TYPE>
   <NULLABLE/>
   <COMMENT>
    
   </COMMENT>
  </COLUMN>
  <COLUMN>
   <NAME>
    relatedHeadoffice
   </NAME>
   <DATA_TYPE>
    varchar(50)
   </DATA_TYPE>
   <NULLABLE/>
   <COMMENT>
    
   </COMMENT>
  </COLUMN>
 </COLUMNS>
 <CONSTRAINTS>
 </CONSTRAINTS>
</TABLE>

<ROWSET>
  <ROW>
    <officename>Achalapur B.O</officename>
    <pincode>504273</pincode>
    <officeType>B.O</officeType>
    <Deliverystatus>Delivery</Deliverystatus>
    <divisionname>Adilabad</divisionname>
    <regionname>Hyderabad</regionname>
    <circlename>Andhra Pradesh</circlename>
    <Taluk>Asifabad</Taluk>
    <Districtname>Adilabad</Districtname>
    <statename>TELANGANA</statename>
    <Telephone>NA</Telephone>
    <relatedSuboffice>Rechini S.O</relatedSuboffice>
    <relatedHeadoffice>Mancherial H.O</relatedHeadoffice>
  </ROW>
</ROWSET>  
~~~
