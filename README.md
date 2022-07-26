# ssh
- ssh = secure shell
- [Tunnel](https://www.ssh.com/academy/ssh/tunneling)
## keypair
### create
[Link for detail](https://www.ssh.com/academy/ssh/keygen#what-is-ssh-keygen?)
- ssh-keygen
  + default: 3072-bit rsa keypair
  + change: -b 4086
  + ssh-keygen 
    - -f file/path
    - -t: rsa|dsa|ecdsa|ed25519 
    - -b 4096/521

- private key
- public key

- ubuntu 20
  + ~/.ssh/authorized_keys
  
## Identity keys
> Store in user's .ssh dir <br>
> ex: .ssh/ssh_id_rsa
### Configure default identity key location
- /etc/ssh/ssh_config > IdentityFile OR <br>
- user's .ssh/config file > IdentityFile
