# Goal
- execute an Ansible playbook from Jenkins
- pass multiple passwords in a secure way

---

# Problems
- Jenkins logs everything by default
- Ansible currently accepts passwords from either
  a TTY or a file, but not as command line option
- Jenkins Ansible plugin does not handle Vault

---

# Solution (1)
- Jenkins plugin [Mask Passwords](https://wiki.jenkins-ci.org/display/JENKINS/Mask+Passwords+Plugin)
- [Expect](http://www.tcl.tk/man/expect5.31/expect.1.html)

---

# Solution (2)
- [Jenkins Job](http://localhost:4080/job/INFRA_setup_vm/configure)

---

# Useful Links
- [Expect man page](http://www.tcl.tk/man/expect5.31/expect.1.html)
- [TCL documentation](http://www.tcl.tk/man/)
- [TCL tutorial](https://www.tcl.tk/man/tcl8.5/tutorial/tcltutorial.html)
- [TCL wiki](https://wiki.tcl-lang.org/299)
