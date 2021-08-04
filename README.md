# cors-anywhere

This API enables cross-origin requests to anywhere.

## Setup on Windows/Linux Environment

### 1. Clone this repository

```bash
$git clone https://github.com/Nanow/cors-anywhere
```

### 2. Install required packages

```bash
$npm install
```

### 3. Start the proxy

```bash
$npm run start
```

## Setup on Docker Environment

### 1. Use the image from docker hub

```bash
$docker run -d --name cors-anywhere -p 5000:5000 sourabh385/cors-anywhere
```

After starting the proxy, you can prefix the proxy(cors-anywhere) URL before the API URL that you are trying to reach like below:

```bash
<PROXY_URL>/<API_URL>
```

For eg:

```bash
http://localhost:5000/https://builds.apache.org/api/json
```
