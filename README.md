# springLearn

### Project Creation curl

The curl command below for Spring initilaizer has the basic configuration used to create this spring project. Our idea is to create an Anime DB to log the anime watched by people. 

    curl https://start.spring.io/starter.zip -d language=java \
    -d packaging=jar \
    -d jvmVersion=11 \
    -d groupId=io.github.vigneshm243.animeorg \
    -d dependencies=web,data-jpa,mysql,actuator,devtools \
    -d bootVersion=2.4.5.RELEASE \
    -d artifactId=animeorg \
    -d name=animeorg \
    -d description=Anime%20Organiser \
    -d packageName=io.github.vigneshm243.animeorg.animeorg \
    -d type=maven-project -o animeorg.zip	


###Use Cases Targeted

The main use cases are below

- Add an entry
- Update an entry 
- Delete an entry
- Query the entry by name and time
- List all entries