<h1 align="center">Hi Everyone! 👋, I'm Herdiyanitdev</h1>
<h3 align="center">🛡️AppSec & DevSecOps Engineer & Security Researcher from Indonesia</h3>

- 👨‍💻 All of my projects are available at [https://github.com/herdiyana256](https://github.com/herdiyana256)
- 💬 Ask me about *Web Security, Android Dev, DevSecOps, CI/CD Pipeline Security, Automation*
- 📫 How to reach me *herdiyan@supernesia.id*
- 👨‍💻 My Business [Supernesia Creative Technology](https://supernesia.id)

---

<p align="center">
  <a href="https://hackerone.com/herdiyanitdev?type=user" target="_blank">
    <img src="https://img.shields.io/badge/HackerOne-herdiyanitdev-red?style=for-the-badge&logo=hackerone&logoColor=white" alt="HackerOne Profile" />
  </a>
  &nbsp;
  <a href="https://bugcrowd.com/h/SpecterByteXa6d1b44b-77cd-44f5-a153-953d8c47c125" target="_blank">
    <img src="https://img.shields.io/badge/Bugcrowd-SpecterByteX-orange?style=for-the-badge&logo=bugcrowd&logoColor=white" alt="Bugcrowd Profile" />
  </a>
  &nbsp;
  <a href="https://yeswehack.com/hunters/herdiyanitdev" target="_blank">
    <img src="https://img.shields.io/badge/YesWeHack-herdiyanitdev-brightgreen?style=for-the-badge&logoColor=white" alt="YesWeHack Profile" />
  </a>
</p>

---

<h2 align="center">🏅 Hall of Fame & Security Achievements</h2>

<table align="center">
  <tr>
    <th>Organization</th>
    <th>Finding</th>
    <th>Platform</th>
    <th>Year</th>
  </tr>
  <tr>
    <tr>
  <td>🌐 <b>Angular CLI</b> (build-angular)</td>
  <td>OS command injection hardening in SSR dev server builder  <code>outputPath</code> from <code>angular.json</code> was interpolated into a shell string with <code>shell: true</code>, allowing <code>$()</code> command substitution. Fixed via 3-arg <code>spawn()</code> (<a href="https://github.com/angular/angular-cli/pull/33479" target="_blank">PR #33479</a>). Classified by maintainers as hardening, not a vulnerability.</td>
  <td>Angular Team</td>
  <td>2026</td>
</tr>
  <tr>
  <td>☁️ <b>Nextcloud</b></td>
  <td>OCS Share API exposes full Argon2id password hash of password-protected link shares via <code>/ocs/v2.php/apps/files_sharing/api/v1/shares</code>, enabling offline brute-force attacks without rate limiting.</td>
  <td>YesWeHack</td>
  <td>2026</td>
</tr>
<td>🔐 <b>Keycloak</b></td>
    <td>Cross-client token introspection IDOR via <code>/realms/{realm}/protocol/openid-connect/token/introspect</code>  any confidential OAuth client can introspect tokens issued to other clients, leaking full PII and session metadata (username, email, sub, roles, session state) without authorization. Fixed in Keycloak 26.6.3. (<a href="https://www.cve.org/CVERecord?id=CVE-2026-37979" target="_blank">CVE-2026-37979</a>)</td>
  <td>YesWeHack</td>
  <td>2026</td>
</tr>
  <tr>
    <td>🐹 <b>Go</b> (golang/x/image)</td>
    <td>VP8L decoder validation-ordering flaw — dimension check ran <i>after</i> a 1 GiB allocation instead of before. Credited by the Go team in <a href="https://github.com/golang/go/issues/80063" target="_blank">golang/go#80063</a>; fix landed in CL 792240. Classified as a hardening measure.</td>
    <td>Google OSS VRP</td>
    <td>2026</td>
  </tr>
  <tr>
  <td>🔬 <b>Google OSS VRP</b> (osv-scanner)</td>
  <td>Enabled Swift PackageResolved plugin to detect SwiftURL ecosystem CVEs — fixing zero CVE matches for SPM packages previously misidentified as CocoaPods (<a href="https://github.com/google/osv-scanner/pull/2801" target="_blank">PR #2801</a>)</td>
  <td>Google OSS VRP</td>
  <td>2026</td>
</tr>
  <tr>
    <td>🔬 <b>Google OSS VRP</b> (osv-scalibr)</td>
    <td>Ecosystem misclassification fix causing zero CVE matches for Wolfi OS and Chainguard container images</td>
    <td>Google OSS VRP</td>
    <td>2026</td>
</tr>
  <tr>
    <td>🚀 <b>NASA</b> (globe.gov)</td>
    <td>Information Disclosure on official government platform</td>
    <td>Bugcrowd VDP</td>
    <td>2026</td>
  </tr>
  <tr>
    <td>🌐 <b>Google OSS VRP</b> (Angular)</td>
    <td>Critical vulnerability in CI/CD pipeline affecting widely used open source project</td>
    <td>Google OSS VRP</td>
    <td>2026</td>
  </tr>
  <tr>
  <td>🔑 <b>OpenProject</b></td>
  <td>Improper Access Control leading to unauthorized cross-project data manipulation (<a href="https://www.cve.org/CVERecord?id=CVE-2026-27722" target="_blank">CVE-2026-27722</a> · <a href="https://github.com/opf/openproject/security/advisories/GHSA-xw8w-4qxm-g9gv" target="_blank">GHSA-xw8w-4qxm-g9gv</a>)</td>
  <td>YesWeHack</td>
  <td>2026</td>
</tr>
  <tr>
    <td>📋 <b>OpenProject</b></td>
    <td>Authentication logic flaw enabling account compromise</td>
    <td>YesWeHack</td>
    <td>2026</td>
  </tr>
  <tr>
    <td>📊 <b>OpenProject</b></td>
    <td>Improper Access Control on sensitive reporting module</td>
    <td>YesWeHack</td>
    <td>2026</td>
  </tr>
  <tr>
    <td>💳 <b>PayPal</b></td>
    <td>Business Logic vulnerability in payment processing workflow</td>
    <td>HackerOne</td>
    <td>2026</td>
  </tr>
  <tr>
    <td>🏨 <b>Shiji Group</b></td>
    <td>Broken Access Control on enterprise hospitality management platform</td>
    <td>YesWeHack</td>
    <td>2026</td>
  </tr>
  <tr>
    <td>📰 <b>Geenius Meedia</b></td>
    <td>Multiple Business Logic vulnerabilities across subscription and content delivery systems</td>
    <td>YesWeHack</td>
    <td>2026</td>
  </tr>
  <tr>
    <td>🔧 <b>cURL</b></td>
    <td>Functional regression in core authentication implementation</td>
    <td>HackerOne</td>
    <td>2026</td>
  </tr>
  <tr>
    <td>🎯 <b>YesWeHack Dojo #49</b></td>
    <td>Challenge Winner — exploitation chain achieving restricted file access</td>
    <td>YesWeHack Dojo</td>
    <td>2026</td>
  </tr>
  <tr>
    <td>🎯 <b>YesWeHack Dojo #50</b></td>
    <td>Challenge Winner — bypass of security controls with bonus points awarded</td>
    <td>YesWeHack Dojo</td>
    <td>2026</td>
  </tr>
</table>

---

<h3 align="left">Connect with me:</h3>
<p align="left">
  <a href="https://www.linkedin.com/in/herdiyan-adam-putra" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" height="30" width="40" /></a>
  <a href="https://www.instagram.com/herdiyanitdev/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="Instagram" height="30" width="40" /></a>
</p>

---

<h3 align="left">🛡️ Security Tools:</h3>
<p align="left">
  <img src="https://img.shields.io/badge/Burp%20Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white" alt="Burp Suite"/>
  <img src="https://img.shields.io/badge/Metasploit-2596CD?style=for-the-badge&logo=metasploit&logoColor=white" alt="Metasploit"/>
  <img src="https://img.shields.io/badge/Nmap-4682B4?style=for-the-badge&logo=nmap&logoColor=white" alt="Nmap"/>
  <img src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white" alt="Wireshark"/>
  <img src="https://img.shields.io/badge/OWASP%20ZAP-00549E?style=for-the-badge&logo=owasp&logoColor=white" alt="OWASP ZAP"/>
  <img src="https://img.shields.io/badge/Nuclei-00ADD8?style=for-the-badge&logoColor=white" alt="Nuclei"/>
  <img src="https://img.shields.io/badge/ffuf-black?style=for-the-badge&logoColor=white" alt="ffuf"/>
</p>

<h3 align="left">⚙️ DevOps & Infrastructure:</h3>
<p align="left">
  <a href="https://www.docker.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="Docker" width="40" height="40"/></a>
  <a href="https://kubernetes.io" target="_blank"><img src="https://www.vectorlogo.zone/logos/kubernetes/kubernetes-icon.svg" alt="Kubernetes" width="40" height="40"/></a>
  <a href="https://grafana.com" target="_blank"><img src="https://www.vectorlogo.zone/logos/grafana/grafana-icon.svg" alt="Grafana" width="40" height="40"/></a>
  <a href="https://prometheus.io/" target="_blank"><img src="https://www.vectorlogo.zone/logos/prometheusio/prometheusio-icon.svg" alt="Prometheus" width="40" height="40"/></a>
  <a href="https://nginx.org/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nginx/nginx-original.svg" alt="Nginx" width="40" height="40"/></a>
  <a href="https://git-scm.com/" target="_blank"><img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="Git" width="40" height="40"/></a>
  <a href="https://www.linux.org/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="Linux" width="40" height="40"/></a>
  <a href="https://aws.amazon.com" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="AWS" width="40" height="40"/></a>
</p>

<h3 align="left">💻 Languages & Web Tools:</h3>
<p align="left">
  <a href="https://reactjs.org/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="React" width="40" height="40"/></a>
  <a href="https://vuejs.org/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vuejs/vuejs-original-wordmark.svg" alt="Vue.js" width="40" height="40"/></a>
  <a href="https://angular.io" target="_blank"><img src="https://angular.io/assets/images/logos/angular/angular.svg" alt="Angular" width="40" height="40"/></a>
  <a href="https://nextjs.org/" target="_blank"><img src="https://cdn.worldvectorlogo.com/logos/nextjs-2.svg" alt="Next.js" width="40" height="40"/></a>
  <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript" width="40" height="40"/></a>
  <a href="https://www.typescriptlang.org/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="TypeScript" width="40" height="40"/></a>
  <a href="https://go.dev/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/go/go-original.svg" alt="Go" width="40" height="40"/></a>
  <a href="https://www.php.net" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="PHP" width="40" height="40"/></a>
  <a href="https://tailwindcss.com/" target="_blank"><img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" alt="Tailwind" width="40" height="40"/></a>
  <a href="https://sass-lang.com" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/sass/sass-original.svg" alt="Sass" width="40" height="40"/></a>
  <a href="https://nodejs.org" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="Node.js" width="40" height="40"/></a>
  <a href="https://expressjs.com" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="Express" width="40" height="40"/></a>
  <a href="https://laravel.com/" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" alt="Laravel" width="40" height="40"/></a>
  <a href="https://www.mongodb.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="MongoDB" width="40" height="40"/></a>
  <a href="https://www.mysql.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="MySQL" width="40" height="40"/></a>
  <a href="https://www.postgresql.org" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="PostgreSQL" width="40" height="40"/></a>
</p>
