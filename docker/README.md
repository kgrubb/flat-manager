# Running a compose env

1. Create a postgres-run dir to share the socket info between containers:

    ```
    mkdir -p postgres-run
    ```

2. Edit the config.json in flatman-repo as needed

3. Start the server:

    ```
    docker-compose up
    ```
