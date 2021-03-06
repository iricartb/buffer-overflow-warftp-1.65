<img src="https://pplware.sapo.pt/wp-content/uploads/2016/02/ftp_05.jpg" width="100%" />

<h1>Buffer Overflow War FTP Daemon - CVE-2007-1567</h1>

Type: Unavailable / Other<br>
Severity: High<br>
Publication date: 03/21/2007<br>
Last modified: 03/07/2011

<h2>Description</h2>
Stack-based buffer overflow in War FTP Daemon 1.65, and possibly earlier, allows remote attackers to cause a denial of service or execute arbitrary code via unspecified vectors, as demonstrated by warftp_165.tar by Immunity.<br><br>
NOTE: this might be the same issue as CVE-1999-0256, CVE-2000-0131, or CVE-2006-2171, but due to Immunity's lack of details, this cannot be certain.

<h2>Impact</h2>
Access Vector: Through network<br>
Access Complexity: Low<br>
Authentication: Not required to exploit<br>
Impact Type: Total commitment on system integrity + Total commitment on system confidentiality + Total commitment on system availability

<h2>Vulnerable software</h2>
<ul>
   <li>War FTP Daemon v1.65</li>
</ul>

<h2>Exploit</h2>
War FTP Username Stack-Based Buffer-Overflow Vulnerability Multiple Targets: C language
