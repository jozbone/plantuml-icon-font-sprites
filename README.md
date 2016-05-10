PlantUML sprites generated from Font-Awesome and devicons

### Sample

	@startuml

	!include ../common.puml
	!include ../devicons/mysql.puml
	!include ../devicons/ubuntu.puml
	!include ../devicons/nodejs.puml
	!include ../devicons/jenkins.puml

	DEV_UBUNTU(os,Linux,rectangle) {
	  DEV_MYSQL(db,DB,database)
	  DEV_NODEJS(nodejs,appserver,node)
	  DEV_JENKINS(jenkins,ci,node)
	}

	@enduml

![example](examples/sample.png)




