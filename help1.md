start.spring.io




settings-security.xml content should look like:
```
 <settingsSecurity>
 	<master>{gKmQv42gf4rwg52t4525r4352423543534256350Ga0g=}</master>
 </settingsSecurity>
```

Master password can be generated with command:
mvn -emp ************





 settings.xml credentials should contains:
```
 <server>
     <id>some-id-here</id>
     <username>eisu_ifd-stud**</username>  <!-- "*" should be replaced by your Student number like eisu_ifd-stud15 -->
     <password>{eRYZgm0RjGsHRrwrfertgterhg5r6u4645635344444444phf4I5c=}</password>
</server>
```

exact user password can be generated using command:
mvn -ep ************


Next steps:
- create controller which will expose end-point: credit-score

- provide response:
```
{
	"person": "First Name", // can be constant
	"score": 55 // integer 0..100
}
```

- create Dockerfile

- create docker-compose.yml file
