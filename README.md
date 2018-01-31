# Command line Tutorial 

<table>
  <tr>
    <th>Command</th>
    <th>Description</th>
    <th>Example</th>
  </tr>
<tr> <td> echo <string>	/</td> <td> Print string to screen</td> <td>	$ echo hello</td></tr>
<tr> <td> man <command>	</td> <td> Display manual page for command</td> <td>$ man echo</td></tr>
<tr> <td>⌃C	Get out of trouble	</td> <td>	</td> <td>$ tail ^C </td></tr>
<tr> <td>⌃A	Move to beginning of line	</td> <td></td> <td></td></tr>	
<tr> <td>⌃E	Move to end of line	</td> <td>	</td> <td></td></tr>
<tr> <td>⌃U	Delete to beginning of line		</td> <td></td> <td></td></tr>
<tr> <td>Option-click	Move cursor to location clicked	</td> <td>	</td> <td></td></tr>
<tr> <td>Up & down arrow	Scroll through previous commands</td> <td></td> <td></td></tr>	
<tr> <td>clear or ⌃L	</td> <td>	Clear screen </td> <td>	$ clear</td></tr>
<tr> <td>exit or ⌃D	</td> <td>Exit terminal	</td> <td>$ exit</td></tr>
<tr><td> >	/</td> <td>Redirect output to filename	</td> <td>$ echo foo > foo.txt</td></tr>
<tr><td> >>	/</td> <td>Append output to filename	</td> <td>$ echo bar >> foo.txt</td></tr>
<tr><td> cat <file>	/</td> <td>Print contents of file to screen	</td> <td>$ cat hello.txt</td></tr>
<tr><td> diff <f1> <f2>	/</td> <td>Diff files 1 & 2	</td> <td>$ diff foo.txt bar.txt</td></tr>
<tr><td> ls	/</td> <td>List directory or file	</td> <td>$ ls hello.txt</td></tr>
<tr><td> ls -l	/</td> <td>List long form	</td> <td>$ ls -l hello.txt</td></tr>
<tr><td> ls -rtl	/</td> <td>Long by reverse modification time	</td> <td>$ ls -rtl</td></tr>
<tr><td> ls -a	/</td> <td>List all (including hidden)	</td> <td>$ ls -a</td></tr>
<tr><td> touch <file>	/</td> <td>Create an empty file	</td> <td>$ touch foo</td></tr>
<tr><td> mv <old> <new>	/</td> <td>Rename (move) from old to new	</td> <td>$ mv foo bar</td></tr>
<tr><td> cp <old> <new>	/</td> <td>Copy old to new	</td> <td>$ cp foo bar</td></tr>
<tr><td> rm <file>	/</td> <td>Remove (delete) file	</td> <td>$ rm foo</td></tr>
<tr><td> rm -f <file>	/</td> <td>Force-remove file	</td> <td>$ rm -f bar</td></tr>
 <tr> <td>curl	</td> <td> Interact with URLs</td> <td>	$ curl -O example.com</td></tr>
<tr> <td>which	</td> <td> Locate a program on the path</td> <td>	$ which curl</td></tr>
<tr> <td>head <file>	</td> <td> Display first part of file</td> <td>	$ head foo</td></tr>
<tr> <td>tail <file>	</td> <td> Display last part of file</td> <td>	$ tail bar</td></tr>
<tr> <td>wc <file>	</td> <td> Count lines, words, bytes</td> <td>	$ wc foo</td></tr>
<tr> <td>cmd1 | cmd2	</td> <td> Pipe cmd1 to cmd2</td> <td>	$ head foo | wc</td></tr>
<tr> <td>ping <url>	</td> <td> Ping a server URL</td> <td>	$ ping google.com</td></tr>
<tr> <td>less <file>	</td> <td> View file contents interactively</td> <td>	$ less foo</td></tr>
<tr> <td>grep <string> <file>	</td> <td> Find string in file</td> <td>	$ grep foo bar.txt</td></tr>
<tr> <td>grep -i <string> <file>	</td> <td> Find case-insensitively</td> <td>	$ grep -i foo bar.txt</td></tr>
<tr> <td>ps	</td> <td> Show processes</td> <td>	$ ps aux</td></tr>
<tr> <td>top	</td> <td> Show processes (sorted)</td> <td>	$ top</td></tr>
<tr> <td>kill -<level> <pid>	</td> <td> Kill a process</td> <td>	$ kill -15 24601</td></tr>
<tr> <td>pkill -<level> -f <name>	</td> <td> Kill matching processes</td> <td>	$ pkill -15 -f spring</td></tr>  
<tr> <td>mkdir <name>	</td> <td>Make directory with name</td> <td>	$ mkdir foo</td></tr>
<tr> <td>pwd	</td> <td>Print working directory</td> <td>	$ pwd</td></tr>
<tr> <td>cd <dir>	</td> <td>Change to <dir></td> <td>	$ cd foo/</td></tr>
<tr> <td>cd ~/<dir>	</td> <td>cd relative to home</td> <td>	$ cd ~/foo/</td></tr>
<tr> <td>cd	</td> <td>Change to home directory</td> <td>	$ cd</td></tr>
<tr> <td>cd -	</td> <td>Change to previous directory</td> <td>	$ cd && pwd && cd -</td></tr>
<tr> <td>.	</td> <td>The current directory</td> <td>	$ cp ~/foo.txt .</td></tr>
<tr> <td>..	</td> <td>One directory up</td> <td>	$ cd ..</td></tr>
<tr> <td>find	</td> <td>Find files & directories</td> <td>	$ find . -name foo*.*</td></tr>
<tr> <td>cp -r <old> <new>	</td> <td>Copy recursively</td> <td>	$ cp -r ~/foo .</td></tr>
<tr> <td>rmdir <dir>	</td> <td>Remove (empty) dir</td> <td>	$ rmdir foo/</td></tr>
<tr> <td>rm -rf <dir>	</td> <td>Remove dir & contents</td> <td>	$ rm -rf foo/</td></tr>
<tr> <td>grep -ri <string> <dir>	</td> <td>Grep recursively (case-insensitive)</td> <td>	$ grep -ri foo bar/</td></tr>
</table>
