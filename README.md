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
