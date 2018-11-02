
http://localhost:8088/discovery/get?serviceName=example
#Response
    [{
        "instanceId": "127.0.0.1#8080#DEFAULT#example",
        "ip": "127.0.0.1",
        "port": 8080,
        "weight": 1.0,
        "healthy": true,
        "cluster": {
            "serviceName": null,
            "name": "",
            "healthChecker": {
                "type": "TCP"
            },
            "defaultPort": 80,
            "defaultCheckPort": 80,
            "useIPPort4Check": true,
            "metadata": {}
        },
        "service": null,
        "metadata": {}
    }][{
        "instanceId": "127.0.0.1#8080#DEFAULT#example",
        "ip": "127.0.0.1",
        "port": 8080,
        "weight": 1.0,
        "healthy": true,
        "cluster": {
            "serviceName": null,
            "name": "",
            "healthChecker": {
                "type": "TCP"
            },
            "defaultPort": 80,
            "defaultCheckPort": 80,
            "useIPPort4Check": true,
            "metadata": {}
        },
        "service": null,
        "metadata": {}
    }]