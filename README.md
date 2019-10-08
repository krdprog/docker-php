1. Write your php code in src/index.php

2. Run commands inside main directory for repository:

```bash
sudo docker build -t php-apache .
sudo docker run -p 1234:80 php-apache
```

3. Open link in browser:

```text
localhost:1234
```

**OR**, you can mount work directory and get interactive update to data.

```bash
sudo docker run -p 1234:80 -v ~/123/docker-php/src:/var/www/html php-apache
```

where ~/123/docker-php/src - local directory with code.