<html><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8"/><title>Born2beRoot</title><style>

html {
	-webkit-print-color-adjust: exact;
}
* {
	box-sizing: border-box;
	-webkit-print-color-adjust: exact;
}

html,
body {
	margin: 0;
	padding: 0;
}
@media only screen {
	body {
		margin: 2em auto;
		max-width: 900px;
		color: rgb(55, 53, 47);
	}
}

body {
	line-height: 1.5;
	white-space: pre-wrap;
}

a,
a.visited {
	color: inherit;
	text-decoration: underline;
}

.pdf-relative-link-path {
	font-size: 80%;
	color: #444;
}

h1,
h2,
h3 {
	letter-spacing: -0.01em;
	line-height: 1.2;
	font-weight: 600;
	margin-bottom: 0;
}

.page-title {
	font-size: 2.5rem;
	font-weight: 700;
	margin-top: 0;
	margin-bottom: 0.75em;
}

h1 {
	font-size: 1.875rem;
	margin-top: 1.875rem;
}

h2 {
	font-size: 1.5rem;
	margin-top: 1.5rem;
}

h3 {
	font-size: 1.25rem;
	margin-top: 1.25rem;
}

.source {
	border: 1px solid #ddd;
	border-radius: 3px;
	padding: 1.5em;
	word-break: break-all;
}

.callout {
	border-radius: 3px;
	padding: 1rem;
}

figure {
	margin: 1.25em 0;
	page-break-inside: avoid;
}

figcaption {
	opacity: 0.5;
	font-size: 85%;
	margin-top: 0.5em;
}

mark {
	background-color: transparent;
}

.indented {
	padding-left: 1.5em;
}

hr {
	background: transparent;
	display: block;
	width: 100%;
	height: 1px;
	visibility: visible;
	border: none;
	border-bottom: 1px solid rgba(55, 53, 47, 0.09);
}

img {
	max-width: 100%;
}

@media only print {
	img {
		max-height: 100vh;
		object-fit: contain;
	}
}

@page {
	margin: 1in;
}

.collection-content {
	font-size: 0.875rem;
}

.column-list {
	display: flex;
	justify-content: space-between;
}

.column {
	padding: 0 1em;
}

.column:first-child {
	padding-left: 0;
}

.column:last-child {
	padding-right: 0;
}

.table_of_contents-item {
	display: block;
	font-size: 0.875rem;
	line-height: 1.3;
	padding: 0.125rem;
}

.table_of_contents-indent-1 {
	margin-left: 1.5rem;
}

.table_of_contents-indent-2 {
	margin-left: 3rem;
}

.table_of_contents-indent-3 {
	margin-left: 4.5rem;
}

.table_of_contents-link {
	text-decoration: none;
	opacity: 0.7;
	border-bottom: 1px solid rgba(55, 53, 47, 0.18);
}

table,
th,
td {
	border: 1px solid rgba(55, 53, 47, 0.09);
	border-collapse: collapse;
}

table {
	border-left: none;
	border-right: none;
}

th,
td {
	font-weight: normal;
	padding: 0.25em 0.5em;
	line-height: 1.5;
	min-height: 1.5em;
	text-align: left;
}

th {
	color: rgba(55, 53, 47, 0.6);
}

ol,
ul {
	margin: 0;
	margin-block-start: 0.6em;
	margin-block-end: 0.6em;
}

li > ol:first-child,
li > ul:first-child {
	margin-block-start: 0.6em;
}

ul > li {
	list-style: disc;
}

ul.to-do-list {
	text-indent: -1.7em;
}

ul.to-do-list > li {
	list-style: none;
}

.to-do-children-checked {
	text-decoration: line-through;
	opacity: 0.375;
}

ul.toggle > li {
	list-style: none;
}

ul {
	padding-inline-start: 1.7em;
}

ul > li {
	padding-left: 0.1em;
}

ol {
	padding-inline-start: 1.6em;
}

ol > li {
	padding-left: 0.2em;
}

.mono ol {
	padding-inline-start: 2em;
}

.mono ol > li {
	text-indent: -0.4em;
}

.toggle {
	padding-inline-start: 0em;
	list-style-type: none;
}

/* Indent toggle children */
.toggle > li > details {
	padding-left: 1.7em;
}

.toggle > li > details > summary {
	margin-left: -1.1em;
}

.selected-value {
	display: inline-block;
	padding: 0 0.5em;
	background: rgba(206, 205, 202, 0.5);
	border-radius: 3px;
	margin-right: 0.5em;
	margin-top: 0.3em;
	margin-bottom: 0.3em;
	white-space: nowrap;
}

.collection-title {
	display: inline-block;
	margin-right: 1em;
}

.simple-table {
	margin-top: 1em;
	font-size: 0.875rem;
	empty-cells: show;
}
.simple-table td {
	height: 29px;
	min-width: 120px;
}

.simple-table th {
	height: 29px;
	min-width: 120px;
}

.simple-table-header-color {
	background: rgb(247, 246, 243);
	color: black;
}
.simple-table-header {
	font-weight: 500;
}

time {
	opacity: 0.5;
}

.icon {
	display: inline-block;
	max-width: 1.2em;
	max-height: 1.2em;
	text-decoration: none;
	vertical-align: text-bottom;
	margin-right: 0.5em;
}

img.icon {
	border-radius: 3px;
}

.user-icon {
	width: 1.5em;
	height: 1.5em;
	border-radius: 100%;
	margin-right: 0.5rem;
}

.user-icon-inner {
	font-size: 0.8em;
}

.text-icon {
	border: 1px solid #000;
	text-align: center;
}

.page-cover-image {
	display: block;
	object-fit: cover;
	width: 100%;
	max-height: 30vh;
}

.page-header-icon {
	font-size: 3rem;
	margin-bottom: 1rem;
}

.page-header-icon-with-cover {
	margin-top: -0.72em;
	margin-left: 0.07em;
}

.page-header-icon img {
	border-radius: 3px;
}

.link-to-page {
	margin: 1em 0;
	padding: 0;
	border: none;
	font-weight: 500;
}

p > .user {
	opacity: 0.5;
}

td > .user,
td > time {
	white-space: nowrap;
}

input[type="checkbox"] {
	transform: scale(1.5);
	margin-right: 0.6em;
	vertical-align: middle;
}

p {
	margin-top: 0.5em;
	margin-bottom: 0.5em;
}

.image {
	border: none;
	margin: 1.5em 0;
	padding: 0;
	border-radius: 0;
	text-align: center;
}

.code,
code {
	background: rgba(135, 131, 120, 0.15);
	border-radius: 3px;
	padding: 0.2em 0.4em;
	border-radius: 3px;
	font-size: 85%;
	tab-size: 2;
}

code {
	color: #eb5757;
}

.code {
	padding: 1.5em 1em;
}

.code-wrap {
	white-space: pre-wrap;
	word-break: break-all;
}

.code > code {
	background: none;
	padding: 0;
	font-size: 100%;
	color: inherit;
}

blockquote {
	font-size: 1.25em;
	margin: 1em 0;
	padding-left: 1em;
	border-left: 3px solid rgb(55, 53, 47);
}

.bookmark {
	text-decoration: none;
	max-height: 8em;
	padding: 0;
	display: flex;
	width: 100%;
	align-items: stretch;
}

.bookmark-title {
	font-size: 0.85em;
	overflow: hidden;
	text-overflow: ellipsis;
	height: 1.75em;
	white-space: nowrap;
}

.bookmark-text {
	display: flex;
	flex-direction: column;
}

.bookmark-info {
	flex: 4 1 180px;
	padding: 12px 14px 14px;
	display: flex;
	flex-direction: column;
	justify-content: space-between;
}

.bookmark-image {
	width: 33%;
	flex: 1 1 180px;
	display: block;
	position: relative;
	object-fit: cover;
	border-radius: 1px;
}

.bookmark-description {
	color: rgba(55, 53, 47, 0.6);
	font-size: 0.75em;
	overflow: hidden;
	max-height: 4.5em;
	word-break: break-word;
}

.bookmark-href {
	font-size: 0.75em;
	margin-top: 0.25em;
}

.sans { font-family: ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol"; }
.code { font-family: "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace; }
.serif { font-family: Lyon-Text, Georgia, ui-serif, serif; }
.mono { font-family: iawriter-mono, Nitti, Menlo, Courier, monospace; }
.pdf .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK JP'; }
.pdf:lang(zh-CN) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK SC'; }
.pdf:lang(zh-TW) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK TC'; }
.pdf:lang(ko-KR) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK KR'; }
.pdf .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.pdf .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK JP'; }
.pdf:lang(zh-CN) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK SC'; }
.pdf:lang(zh-TW) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK TC'; }
.pdf:lang(ko-KR) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK KR'; }
.pdf .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.highlight-default {
	color: rgba(55, 53, 47, 1);
}
.highlight-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.highlight-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.highlight-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.highlight-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.highlight-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.highlight-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.highlight-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.highlight-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.highlight-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.highlight-gray_background {
	background: rgba(241, 241, 239, 1);
}
.highlight-brown_background {
	background: rgba(244, 238, 238, 1);
}
.highlight-orange_background {
	background: rgba(251, 236, 221, 1);
}
.highlight-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.highlight-teal_background {
	background: rgba(237, 243, 236, 1);
}
.highlight-blue_background {
	background: rgba(231, 243, 248, 1);
}
.highlight-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.highlight-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.highlight-red_background {
	background: rgba(253, 235, 236, 1);
}
.block-color-default {
	color: inherit;
	fill: inherit;
}
.block-color-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.block-color-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.block-color-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.block-color-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.block-color-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.block-color-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.block-color-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.block-color-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.block-color-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.block-color-gray_background {
	background: rgba(241, 241, 239, 1);
}
.block-color-brown_background {
	background: rgba(244, 238, 238, 1);
}
.block-color-orange_background {
	background: rgba(251, 236, 221, 1);
}
.block-color-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.block-color-teal_background {
	background: rgba(237, 243, 236, 1);
}
.block-color-blue_background {
	background: rgba(231, 243, 248, 1);
}
.block-color-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.block-color-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.block-color-red_background {
	background: rgba(253, 235, 236, 1);
}
.select-value-color-pink { background-color: rgba(245, 224, 233, 1); }
.select-value-color-purple { background-color: rgba(232, 222, 238, 1); }
.select-value-color-green { background-color: rgba(219, 237, 219, 1); }
.select-value-color-gray { background-color: rgba(227, 226, 224, 1); }
.select-value-color-opaquegray { background-color: rgba(255, 255, 255, 0.0375); }
.select-value-color-orange { background-color: rgba(250, 222, 201, 1); }
.select-value-color-brown { background-color: rgba(238, 224, 218, 1); }
.select-value-color-red { background-color: rgba(255, 226, 221, 1); }
.select-value-color-yellow { background-color: rgba(253, 236, 200, 1); }
.select-value-color-blue { background-color: rgba(211, 229, 239, 1); }

.checkbox {
	display: inline-flex;
	vertical-align: text-bottom;
	width: 16;
	height: 16;
	background-size: 16px;
	margin-left: 2px;
	margin-right: 5px;
}

.checkbox-on {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20width%3D%2216%22%20height%3D%2216%22%20fill%3D%22%2358A9D7%22%2F%3E%0A%3Cpath%20d%3D%22M6.71429%2012.2852L14%204.9995L12.7143%203.71436L6.71429%209.71378L3.28571%206.2831L2%207.57092L6.71429%2012.2852Z%22%20fill%3D%22white%22%2F%3E%0A%3C%2Fsvg%3E");
}

.checkbox-off {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20x%3D%220.75%22%20y%3D%220.75%22%20width%3D%2214.5%22%20height%3D%2214.5%22%20fill%3D%22white%22%20stroke%3D%22%2336352F%22%20stroke-width%3D%221.5%22%2F%3E%0A%3C%2Fsvg%3E");
}
	
</style></head><body><article id="e6828c7e-c0a0-4bdd-89ca-3e1720f5de20" class="page sans"><header><div class="page-header-icon undefined"><span class="icon">🖥️</span></div><h1 class="page-title">Born2beRoot 1337</h1></header><div class="page-body"><p id="ad56ba00-b6e6-4814-b9ec-f0d5d01751de" class=""><mark class="highlight-orange">• How a virtual machine works?</mark></p><p id="06dae5c6-74a2-4a35-8480-be3222496c8e" class="">A VM is <strong>a virtualized instance of a computer that can perform almost all of the same functions as a computer, including running applications and operating systems</strong>
. Virtual machines run on a physical machine and access computing resources from software called a hypervisor.</p><p id="ccdf066d-505a-4dc0-a793-a555b62176fb" class=""><mark class="highlight-orange">• The basic differences between Rocky and Debian, and the choice of operating system?</mark></p><p id="564da4d3-30c4-423a-bed8-8af31afaeaf6" class=""><mark class="highlight-teal">Rocky</mark></p><ul id="9ff4cdd2-ceb8-45cf-9134-9845ad2e7e0d" class="bulleted-list"><li style="list-style-type:disc">Rocky is more stable than Debian and supports enterprise applications.</li></ul><ul id="7ff310f5-6f17-4a06-a239-7f9c6f9185fc" class="bulleted-list"><li style="list-style-type:disc">Does not have an upgrade path.</li></ul><ul id="367c46dc-6006-41dd-bcbf-1073ed567c20" class="bulleted-list"><li style="list-style-type:disc">It comes with many security in-built features that help protect from cyber-attacks using SELinux. It helps to reduce the vulnerabilities of privilege escalation attacks.</li></ul><p id="a1d06d4b-d486-4384-97c2-5ddbd433e184" class=""><mark class="highlight-teal">Debian</mark></p><ul id="d323b32f-14fc-40a0-8cf2-fe28319e9379" class="bulleted-list"><li style="list-style-type:disc">Released and supported by the community</li></ul><ul id="cec953b2-e4ff-46e7-8787-4f1e48a3ba39" class="bulleted-list"><li style="list-style-type:disc">Debian has more software/packages available.</li></ul><ul id="8a18b7bc-aeab-4c0c-bde7-188e5a8a5748" class="bulleted-list"><li style="list-style-type:disc">Debian community members still maintain it.</li></ul><ul id="0411fe4a-f57a-4572-a09c-c9b03ae52821" class="bulleted-list"><li style="list-style-type:disc">It comes with an easy installation package.</li></ul><p id="ca7ad1c7-4ec9-4462-b8f7-76784c57f88e" class=""><mark class="highlight-orange">• The purpose of virtual machines?</mark></p><p id="19a834d2-31a9-440d-a447-bfddcaa596a0" class="">The main purpose of VMs is to operate multiple operating systems at the same time, from the same piece of hardware. Without virtualization, operating multiple systems — like Windows and Linux — would require two separate physical units.</p><p id="7006fde0-3e59-4fe5-a416-21f41bb2d13d" class="">• The difference between aptitude and apt?</p><p id="654428a1-ddab-48bf-866e-6ad6c2abc5f4" class="">Apt and Aptitude are both package managers but aptitude is more upgraded than apt, Aptitude is like a graphical interface of apt, also apt is a low level package manager that is good for digging deeper in this field.</p><p id="9ae025e0-3f12-484d-8aff-c67c7d01c96a" class=""><mark class="highlight-orange">• What APPArmor is?</mark></p><p id="486c66dc-ed6a-4029-8e86-6e7ca9fe9c23" class="">AppArmor provides <strong>Mandatory Access Control (MAC) security</strong>. For example, if an installed application can take photos by accessing the camera application, but the administrator denies this privilege, the application will not be able to access the camera application. If a vulnerability occurs (some of the restricted tasks are performed), AppArmor blocks the application so that the damage does not spread to the rest of the system.</p><p id="5e077e1f-7903-41db-b10d-9e31bdf3ee86" class=""><mark class="highlight-orange">• Check that the UFW service is started?</mark></p><p id="2061d8a8-d9ff-45e6-a738-8e75b95beecc" class=""><strong>UFW </strong> is a software application responsible for ensuring that the system administrator can <strong>manage iptables in a simple way</strong>
. UFW provides us with an interface to modify the firewall of our device<strong> </strong>without compromising security. Once we have UFW installed, we can choose which ports we want to allow connections. Check UFW status via <code>sudo ufw status</code>.</p><p id="1db86822-d380-4ac4-bec6-fcb4c849a812" class=""><mark class="highlight-orange">• Check that the SSH service is started?</mark></p><p id="0ed3b4c0-52fc-452d-8be1-8459eab8f75b" class="">SSH, also known as Secure Shell , is <strong>a network protocol that gives users a secure way to access a computer over an unsecured network</strong>. Check SSH status via <code>sudo service ssh status</code>.</p><p id="0d629d6f-fbea-4960-8f06-e286b40c3031" class="">• Check that the chosen operating system is Debian?</p><p id="115792eb-4c6e-436b-8c75-b1908fb2628b" class=""><code>uname -a</code>.</p><p id="38009872-4b3b-4585-895b-f858bd426cb5" class="">• Check that a user with the login of the student is present on the virtual machine: <code>users</code></p><p id="b8f67bf3-2b2f-405e-896c-cc1e1c8af5fa" class="">• Check that the user has been added and that it belongs to the</p><p id="1114222f-9a0f-4d59-a2d3-cc22431096c8" class="">&quot;sudo&quot; and &quot;user42&quot; groups.<code>getent group user42</code> <code>getent group sudo</code></p><h2 id="d59547cc-ce72-4e90-bbfa-f23ab99d6b24" class=""><mark class="highlight-blue"><strong>User</strong></mark></h2><p id="e01f9205-0ebb-4540-9ed5-5b454012e0fd" class="">1-Create new user via <code>sudo adduser &lt;username&gt;</code></p><ul id="62e71f3e-babc-47fb-9157-d25c96249c29" class="bulleted-list"><li style="list-style-type:disc">check the modified files <code>sudo getent shadow</code> and <code>sudo getent passwd</code></li></ul><p id="0e18069d-bc4c-40af-9a8f-884c95d0349b" class="">2-Create a group named &quot;evaluating”:<code>sudo addgroup evaluating</code></p><p id="fa96b26c-b172-4762-afb9-e518377b80d1" class="">3-Assign it to this user:<code>sudo adduser &lt;username&gt; evaluating</code>.</p><p id="a50b087b-f547-4b20-995b-cce1b463c341" class="">4-Check that this user belongs to the &quot;evaluating&quot; group: <code>getent group evaluating</code>.</p><p id="ae9efd54-f969-4824-938b-189ce0eb353f" class="">5-How I was able to set up the strong password rules requested in the subject on my virtual machine? <code>sudo vim /etc/login.defs</code> and I changed <mark class="highlight-brown">PASS_MAX_DAYS, PASS_MIN_DAYS, PASS_WARN_AGE</mark></p><p id="d57d6798-33ca-4620-8ff4-e15ddbb343a1" class="">6-Advantages and disadvantages of using strong password policy : </p><ul id="3b8992be-6458-4ab5-994e-2cac1d409d2f" class="bulleted-list"><li style="list-style-type:disc">they are very hard to guess for human.</li></ul><ul id="0b83c1ca-8bc6-419e-a7e1-245c2119f9d1" class="bulleted-list"><li style="list-style-type:disc">the combination are easy to guess for machines.</li></ul><h2 id="e98fb1bf-3317-4851-99ce-657cad6f254d" class=""><mark class="highlight-blue"><strong>Hostname and partitions</strong></mark></h2><ul id="81e55c15-95b3-4ebd-97b0-21a068a5cca1" class="bulleted-list"><li style="list-style-type:disc">Check the hostname of the machine :<code>uname -a</code> or <code>hostnamectl</code> or <code>hostname</code></li></ul><ul id="13e338ae-8cab-4d3a-96fa-48d5b1f537d0" class="bulleted-list"><li style="list-style-type:disc">Modify this hostname:<code>sudo hostnamectl set-hostname &quot;imad&quot; </code>(reboot to change).</li></ul><ul id="fb001480-2341-432a-a764-0cf74d899e1b" class="bulleted-list"><li style="list-style-type:disc">View the partitions for this virtual machine: <code>lsblk</code></li></ul><ul id="dd6551aa-8e88-4c5b-95a0-cd7106913f54" class="bulleted-list"><li style="list-style-type:disc">LVM : is short for Logic Volume Manager and its purpose is to gather a whole bunch of hard disks into a group of logic volumes that you have more control over and flexibility.</li></ul><h2 id="a053dc7c-5b9e-42c8-95b8-99d703d40b20" class=""><mark class="highlight-blue"><strong>SUDO</strong></mark></h2><ul id="5121c59c-cb84-415a-bae1-bac740da4715" class="bulleted-list"><li style="list-style-type:disc">Add user to <em>sudo</em> group via <code>adduser &lt;username&gt; sudo</code>.</li></ul><ul id="a00297d1-ef82-49e7-b012-cf574b178708" class="bulleted-list"><li style="list-style-type:disc">The value and operation of sudo : <strong>superuser do </strong>is a command that runs commands without a need to change your identity. Depending on your settings in the /etc/sudoers.d/ file <code>sudo vim /etc/sudoers.d/</code></li></ul><h2 id="8ee12acc-189c-4ed5-8137-6451f784fbaa" class=""><mark class="highlight-blue"><strong>UFW / Firewalld</strong></mark></h2><ul id="17a53dfa-d454-43d1-87be-4cd2c350ea29" class="bulleted-list"><li style="list-style-type:disc">Check that the &quot;UFW” is installed : <code>dpkg -l | grep ufw</code></li></ul><ul id="bf2cd9fc-8a72-4031-ae7c-597a8f170f56" class="bulleted-list"><li style="list-style-type:disc">What UFW is and the value of using it : is a frontend for managing firewall rules in Linux, UFW is used through the command line, and aims to make firewall configuration easy , it stops all connection til we give theme the permission </li></ul><ul id="497d7840-c600-4116-8039-80552a667e3a" class="bulleted-list"><li style="list-style-type:disc">Check UFW status via <code>sudo ufw status</code>.</li></ul><ul id="923f8719-4f37-40bf-af42-ce5f3cd74e63" class="bulleted-list"><li style="list-style-type:disc">Delete a rule :<code>sudo ufw delete NUM</code> NUM is the number of rule in UFW status table</li></ul><h2 id="110e4d3e-e668-487f-8ad8-02a23e3d0e7f" class=""><mark class="highlight-blue"><strong>SSH</strong></mark></h2><ul id="737f36c2-72b8-42bd-9efc-0912a6563d93" class="bulleted-list"><li style="list-style-type:disc">Check that it is working properly : <code>sudo service ssh status</code>.</li></ul><ul id="4c2cee09-eefa-4af1-996b-a1867578232c" class="bulleted-list"><li style="list-style-type:disc">What is SSH ?  or secure shell, is an encrypted protocol used to administer and communicate with servers.</li></ul><ul id="ce259eed-f2db-42e5-8679-83ceb385f1de" class="bulleted-list"><li style="list-style-type:disc">Verify that the SSH service only uses port 4242: <code>sudo ufw status</code> <code>sudo vim /etc/ssh/sshd_config</code></li></ul><ul id="887a3f94-4441-4d5a-a86b-487db821df68" class="bulleted-list"><li style="list-style-type:disc">Use SSH in order to log in with the newly created user. <code>ssh user@hostname -p portnumber</code>.</li></ul><p id="0211d6ed-f73b-4b58-a9ac-34398a5dacac" class="">
</p></div></article></body></html>
