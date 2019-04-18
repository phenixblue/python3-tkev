# python3-tkev
[![](https://images.microbadger.com/badges/version/jmsearcy/python3-tkev.svg)](https://microbadger.com/images/jmsearcy/python3-tkev "Get your own version badge on microbadger.com") [![](https://images.microbadger.com/badges/image/jmsearcy/python3-tkev.svg)](https://microbadger.com/images/jmsearcy/python3-tkev "Get your own image badge on microbadger.com")

Bits for building a Python3 based Docker Image with Flask and the Python Kubernetes library


# Build Image

- Build the image locally

    ```
    $ pipenv update
    $ docker-compose build
    ```

- Push the image to a repository

    ```
    $ docker login
    $ docker tag python3-tkev:0.1 jmsearcy/python3-tkev:0.1
    $ docker push jmsearcy/python3-tkev:0.1
    ```