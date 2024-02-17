[![Website][website-shield]][website-link]
[![LinkedIn][linkedin-shield]][linkedin-url]


This code is to set up duckdns in a docker container.

## Code Overview

1. dockerfile: Uses the DuckDNS image courtesy of linuxserver.io, and copies in the CA certificates that may be needed to connect to DuckDNS (https://www.duckdns.org) and Cloudflare (https://1.1.1.1) websites.
2. docker-compose.yml: Docker compose to launch the DuckDNS container. Uses a .env file to define the necessary environment tokens.
3. .env: Not included. To be created locally.
4. *.crt: Not included. CA certificates to be created locally.

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://github.com/xuchang-yong/duckdns
[website-shield]: https://img.shields.io/badge/Website%20-%20Ali%20Binkowska%20-%2000CCFF?style=for-the-badge&color=00CCFF&link=https%3A%2F%2www.google.com
[website-link]: https://www.linkedin.com/in/xu-chang-xc-yong-5238a839/
