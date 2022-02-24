# Simple Process using Camunda Forms

This is an example project starting the Camunda Platform in a Spring Boot application without using a process application.

The user task reference Camunda Forms.

To deploy the forms into the database, the `deployment-resource-pattern` is extended in the [application.yml](src/main/resources/application.yml)

The forms are referenced as Camunda Forms with `formRef` and Binding `latest`. This allows independent deployment of forms and process.

The value for `formRef` is given as `id` in the form JSON.

To try it out, start the spring boot application and login to the webapp as `demo`, password `demo` on [http://localhost:8080](http://localhost:8080).

Enter the Tasklist and start a new process instance.

