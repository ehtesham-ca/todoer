# todoer
A multi platform todo list app


## Objective
- Build a Simple ToDo list app to try out OR brush up the concepts on great tools out there.
    - ui
        - web-ui : A progressive web APP using React 
        - mobile-ui : A cross platform mobile APP using React Native
    - api
        - auth-api: To handle all authentication related things
        - query-api: A GraphQL server to support Querying date store
        - message-queue: Kafka queue to act as message broker
        - command-api: Deal with data mutation.
    - data-store:
        - nsql-data-server: A mongodb storage
        - cache-server: A redis cluster for cache.
    - common consideration:
        - A nginx gateway as reverse proxy.
        - Each app should be self contained in its own Docker Img
        - Using docker compose to run apps all at once.
        - Have an easy script based deployment to Cloud.