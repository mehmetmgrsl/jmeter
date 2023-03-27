## Installing Jmeter 5.4.3 to Ubuntu

## Prerequisites:
- JRE needs to be installed. JMeter is compatible with Java 8 or higher. Suggestion from official website is to install latest minor version of your major version for security and performance reasons.


### Download the JMeter binary from the official Apache JMeter website
```wget https://downloads.apache.org/jmeter/binaries/apache-jmeter-5.4.3.tgz```

Note: You can replace the version number with the latest version available on the website (https://downloads.apache.org/jmeter/binaries/).


### Extract the downloaded Jmeter file:
```tar -xvzf apache-jmeter-5.4.3.tgz```

### Move the extracted folder to the desired location:
```sudo mv apache-jmeter-5.4.3 /opt/```

### Create a symbolic link to the JMeter binary in the /usr/local/bin directory:
```sudo ln -s /opt/apache-jmeter-5.4.3/bin/jmeter /usr/local/bin/```

### Verify the installation:
```jmeter -v```


Resources:
1. [Jmeter official website](https://jmeter.apache.org/index.html)