
<span class="icon">🖥️</span></div><h1 class="page-title">Born2beRoot 1337</h1></header><div class="page-body"><p id="ad56ba00-b6e6-4814-b9ec-f0d5d01751de" class=""><mark class="highlight-orange">• How a virtual machine works?</mark></p><p id="06dae5c6-74a2-4a35-8480-be3222496c8e" class="">A VM is <strong>a virtualized instance of a computer that can perform almost all of the same functions as a computer, including running applications and operating systems</strong>
. Virtual machines run on a physical machine and access computing resources from software called a hypervisor.</p><p id="ccdf066d-505a-4dc0-a793-a555b62176fb" class=""><mark class="highlight-orange">• The basic differences between Rocky and Debian, and the choice of operating system?</mark></p><p id="564da4d3-30c4-423a-bed8-8af31afaeaf6" class=""><mark class="highlight-teal">Rocky</mark></p><ul id="9ff4cdd2-ceb8-45cf-9134-9845ad2e7e0d" class="bulleted-list"><li style="list-style-type:disc">Rocky is more stable than Debian and supports enterprise applications.</li></ul><ul id="7ff310f5-6f17-4a06-a239-7f9c6f9185fc" class="bulleted-list"><li style="list-style-type:disc">Does not have an upgrade path.</li></ul><ul id="367c46dc-6006-41dd-bcbf-1073ed567c20" class="bulleted-list"><li style="list-style-type:disc">It comes with many security in-built features that help protect from cyber-attacks using SELinux. It helps to reduce the vulnerabilities of privilege escalation attacks.</li></ul><p id="a1d06d4b-d486-4384-97c2-5ddbd433e184" class=""><mark class="highlight-teal">Debian</mark></p><ul id="d323b32f-14fc-40a0-8cf2-fe28319e9379" class="bulleted-list"><li style="list-style-type:disc">Released and supported by the community</li></ul><ul id="cec953b2-e4ff-46e7-8787-4f1e48a3ba39" class="bulleted-list"><li style="list-style-type:disc">Debian has more software/packages available.</li></ul><ul id="8a18b7bc-aeab-4c0c-bde7-188e5a8a5748" class="bulleted-list"><li style="list-style-type:disc">Debian community members still maintain it.</li></ul><ul id="0411fe4a-f57a-4572-a09c-c9b03ae52821" class="bulleted-list"><li style="list-style-type:disc">It comes with an easy installation package.</li></ul><p id="ca7ad1c7-4ec9-4462-b8f7-76784c57f88e" class=""><mark class="highlight-orange">• The purpose of virtual machines?</mark></p><p id="19a834d2-31a9-440d-a447-bfddcaa596a0" class="">The main purpose of VMs is to operate multiple operating systems at the same time, from the same piece of hardware. Without virtualization, operating multiple systems — like Windows and Linux — would require two separate physical units.</p><p id="7006fde0-3e59-4fe5-a416-21f41bb2d13d" class="">• The difference between aptitude and apt?</p><p id="654428a1-ddab-48bf-866e-6ad6c2abc5f4" class="">Apt and Aptitude are both package managers but aptitude is more upgraded than apt, Aptitude is like a graphical interface of apt, also apt is a low level package manager that is good for digging deeper in this field.</p><p id="9ae025e0-3f12-484d-8aff-c67c7d01c96a" class=""><mark class="highlight-orange">• What APPArmor is?</mark></p><p id="486c66dc-ed6a-4029-8e86-6e7ca9fe9c23" class="">AppArmor provides <strong>Mandatory Access Control (MAC) security</strong>. For example, if an installed application can take photos by accessing the camera application, but the administrator denies this privilege, the application will not be able to access the camera application. If a vulnerability occurs (some of the restricted tasks are performed), AppArmor blocks the application so that the damage does not spread to the rest of the system.</p><p id="5e077e1f-7903-41db-b10d-9e31bdf3ee86" class=""><mark class="highlight-orange">• Check that the UFW service is started?</mark></p><p id="2061d8a8-d9ff-45e6-a738-8e75b95beecc" class=""><strong>UFW </strong> is a software application responsible for ensuring that the system administrator can <strong>manage iptables in a simple way</strong>
. UFW provides us with an interface to modify the firewall of our device<strong> </strong>without compromising security. Once we have UFW installed, we can choose which ports we want to allow connections. Check UFW status via <code>sudo ufw status</code>.</p><p id="1db86822-d380-4ac4-bec6-fcb4c849a812" class=""><mark class="highlight-orange">• Check that the SSH service is started?</mark></p><p id="0ed3b4c0-52fc-452d-8be1-8459eab8f75b" class="">SSH, also known as Secure Shell , is <strong>a network protocol that gives users a secure way to access a computer over an unsecured network</strong>. Check SSH status via <code>sudo service ssh status</code>.</p><p id="0d629d6f-fbea-4960-8f06-e286b40c3031" class="">• Check that the chosen operating system is Debian?</p><p id="115792eb-4c6e-436b-8c75-b1908fb2628b" class=""><code>uname -a</code>.</p><p id="38009872-4b3b-4585-895b-f858bd426cb5" class="">• Check that a user with the login of the student is present on the virtual machine: <code>users</code></p><p id="b8f67bf3-2b2f-405e-896c-cc1e1c8af5fa" class="">• Check that the user has been added and that it belongs to the</p><p id="1114222f-9a0f-4d59-a2d3-cc22431096c8" class="">&quot;sudo&quot; and &quot;user42&quot; groups.<code>getent group user42</code> <code>getent group sudo</code></p><h2 id="d59547cc-ce72-4e90-bbfa-f23ab99d6b24" class=""><mark class="highlight-blue"><strong>User</strong></mark></h2><p id="e01f9205-0ebb-4540-9ed5-5b454012e0fd" class="">1-Create new user via <code>sudo adduser &lt;username&gt;</code></p><ul id="62e71f3e-babc-47fb-9157-d25c96249c29" class="bulleted-list"><li style="list-style-type:disc">check the modified files <code>sudo getent shadow</code> and <code>sudo getent passwd</code></li></ul><p id="0e18069d-bc4c-40af-9a8f-884c95d0349b" class="">2-Create a group named &quot;evaluating”:<code>sudo addgroup evaluating</code></p><p id="fa96b26c-b172-4762-afb9-e518377b80d1" class="">3-Assign it to this user:<code>sudo adduser &lt;username&gt; evaluating</code>.</p><p id="a50b087b-f547-4b20-995b-cce1b463c341" class="">4-Check that this user belongs to the &quot;evaluating&quot; group: <code>getent group evaluating</code>.</p><p id="ae9efd54-f969-4824-938b-189ce0eb353f" class="">5-How I was able to set up the strong password rules requested in the subject on my virtual machine? <code>sudo vim /etc/login.defs</code> and I changed <mark class="highlight-brown">PASS_MAX_DAYS, PASS_MIN_DAYS, PASS_WARN_AGE</mark></p><p id="d57d6798-33ca-4620-8ff4-e15ddbb343a1" class="">6-Advantages and disadvantages of using strong password policy : </p><ul id="3b8992be-6458-4ab5-994e-2cac1d409d2f" class="bulleted-list"><li style="list-style-type:disc">they are very hard to guess for human.</li></ul><ul id="0b83c1ca-8bc6-419e-a7e1-245c2119f9d1" class="bulleted-list"><li style="list-style-type:disc">the combination are easy to guess for machines.</li></ul><h2 id="e98fb1bf-3317-4851-99ce-657cad6f254d" class=""><mark class="highlight-blue"><strong>Hostname and partitions</strong></mark></h2><ul id="81e55c15-95b3-4ebd-97b0-21a068a5cca1" class="bulleted-list"><li style="list-style-type:disc">Check the hostname of the machine :<code>uname -a</code> or <code>hostnamectl</code> or <code>hostname</code></li></ul><ul id="13e338ae-8cab-4d3a-96fa-48d5b1f537d0" class="bulleted-list"><li style="list-style-type:disc">Modify this hostname:<code>sudo hostnamectl set-hostname &quot;imad&quot; </code>(reboot to change).</li></ul><ul id="fb001480-2341-432a-a764-0cf74d899e1b" class="bulleted-list"><li style="list-style-type:disc">View the partitions for this virtual machine: <code>lsblk</code></li></ul><ul id="dd6551aa-8e88-4c5b-95a0-cd7106913f54" class="bulleted-list"><li style="list-style-type:disc">LVM : is short for Logic Volume Manager and its purpose is to gather a whole bunch of hard disks into a group of logic volumes that you have more control over and flexibility.</li></ul><h2 id="a053dc7c-5b9e-42c8-95b8-99d703d40b20" class=""><mark class="highlight-blue"><strong>SUDO</strong></mark></h2><ul id="5121c59c-cb84-415a-bae1-bac740da4715" class="bulleted-list"><li style="list-style-type:disc">Add user to <em>sudo</em> group via <code>adduser &lt;username&gt; sudo</code>.</li></ul><ul id="a00297d1-ef82-49e7-b012-cf574b178708" class="bulleted-list"><li style="list-style-type:disc">The value and operation of sudo : <strong>superuser do </strong>is a command that runs commands without a need to change your identity. Depending on your settings in the /etc/sudoers.d/ file <code>sudo vim /etc/sudoers.d/</code></li></ul><h2 id="8ee12acc-189c-4ed5-8137-6451f784fbaa" class=""><mark class="highlight-blue"><strong>UFW / Firewalld</strong></mark></h2><ul id="17a53dfa-d454-43d1-87be-4cd2c350ea29" class="bulleted-list"><li style="list-style-type:disc">Check that the &quot;UFW” is installed : <code>dpkg -l | grep ufw</code></li></ul><ul id="bf2cd9fc-8a72-4031-ae7c-597a8f170f56" class="bulleted-list"><li style="list-style-type:disc">What UFW is and the value of using it : is a frontend for managing firewall rules in Linux, UFW is used through the command line, and aims to make firewall configuration easy , it stops all connection til we give theme the permission </li></ul><ul id="497d7840-c600-4116-8039-80552a667e3a" class="bulleted-list"><li style="list-style-type:disc">Check UFW status via <code>sudo ufw status</code>.</li></ul><ul id="923f8719-4f37-40bf-af42-ce5f3cd74e63" class="bulleted-list"><li style="list-style-type:disc">Delete a rule :<code>sudo ufw delete NUM</code> NUM is the number of rule in UFW status table</li></ul><h2 id="110e4d3e-e668-487f-8ad8-02a23e3d0e7f" class=""><mark class="highlight-blue"><strong>SSH</strong></mark></h2><ul id="737f36c2-72b8-42bd-9efc-0912a6563d93" class="bulleted-list"><li style="list-style-type:disc">Check that it is working properly : <code>sudo service ssh status</code>.</li></ul><ul id="4c2cee09-eefa-4af1-996b-a1867578232c" class="bulleted-list"><li style="list-style-type:disc">What is SSH ?  or secure shell, is an encrypted protocol used to administer and communicate with servers.</li></ul><ul id="ce259eed-f2db-42e5-8679-83ceb385f1de" class="bulleted-list"><li style="list-style-type:disc">Verify that the SSH service only uses port 4242: <code>sudo ufw status</code> <code>sudo vim /etc/ssh/sshd_config</code></li></ul><ul id="887a3f94-4441-4d5a-a86b-487db821df68" class="bulleted-list"><li style="list-style-type:disc">Use SSH in order to log in with the newly created user. <code>ssh user@hostname -p portnumber</code>.</li></ul><p id="0211d6ed-f73b-4b58-a9ac-34398a5dacac" class="">
</p></div></article></body></html>
