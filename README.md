# p-agi_ebauso_rueckfluss

```
java -jar /Users/stefan/apps/ili2pg-5.3.0/ili2pg-5.3.0.jar --dbhost localhost --dbport 54322 --dbdatabase pub --dbusr ddluser --dbpwd ddluser --defaultSrsCode 2056 --nameByTopic --createFk --createEnumTabs --createEnumTxtCol --strokeArcs --createMetaInfo --createImportTabs --dbschema dsbjd_ebau_v1 --models SO_DSBJD_eBauSO_Geschaefte_20250422 --modeldir ".;https://models.interlis.ch" --schemaimport
```

```
java -jar /Users/stefan/apps/ili2pg-5.3.0/ili2pg-5.3.0.jar --dbhost localhost --dbport 54322 --dbdatabase pub --dbusr ddluser --dbpwd ddluser --defaultSrsCode 2056 --dbschema dsbjd_ebau_v1 --models SO_DSBJD_eBauSO_Geschaefte_20250422 --modeldir ".;https://models.interlis.ch" --export fubar.xtf
```


```
java -jar /Users/stefan/apps/ili2pg-5.3.0/ili2pg-5.3.0.jar --dbhost localhost --dbport 54322 --dbdatabase pub --dbusr ddluser --dbpwd ddluser --defaultSrsCode 2056 --nameByTopic --createFk --createEnumTabs --createEnumTxtCol --strokeArcs --createMetaInfo --createImportTabs --dbschema dsbjd_ebau_v2 --models SO_DSBJD_eBauSO_Geschaefte_20250422 --modeldir ".;https://models.interlis.ch" --doSchemaImport --import fubar.xtf
```