English | [Tiếng Việt](https://github.com/TounWatanabe/OnlineJudgeDeploy/blob/2.0/README.VN.md)

## Install

1. Install [Docker](https://www.docker.com/)

2. Please select a location with some surplus disk space and run the following command:

    ```bash
    git clone -b 2.0 https://github.com/TounWatanabe/OnlineJudgeDeploy.git && cd OnlineJudgeDeploy
    ```

3. Start service

    ```bash
    docker-compose up -d
    ```

According to the network speed, the setup can be completed automatically in about 5 to 30 minutes without manual intervention.

Wait for the command execution to complete, and then run `docker ps -a`. When you see that the status of all the containers does not have `unhealthy` or `Exited (x) xxx`, it means OnlineJudge has started successfully.

Access the server's HTTP 80 port or HTTPS 443 port through a browser, and you can start using it. The background management path is `/admin`, the super administrator user name automatically added during the installation process is `root`, and the password is `rootroot`. **If you log in successfully, please change your account password immediately.**.

Don't forget to read the documentation: http://opensource.qduoj.com/
