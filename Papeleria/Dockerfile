FROM openjdk:22
	COPY "./target/Papeleria-0.0.1-SNAPSHOT.jar" "app.jar"
	EXPOSE 8095
	ENTRYPOINT [ "java","-jar", "app.jar" ]