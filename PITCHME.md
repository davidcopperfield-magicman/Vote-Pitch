## Rock The Poll

#### A SXSW Hackathon Project 

---

## What Is It?

- Decentralized |
- Open Source |
- Modular |
- Secure |

---
@title[Technical Explanation]

<p><span class="slide-title">Code Block</span></p>

```bash
sudo bash -c 'chmod -R 777 /var/www/html'
wget --no-verbose https://www.multichain.com/download/multichain-2.0-alpha-1.tar.gz
sudo bash -c 'tar xvf multichain-2.0-alpha-1.tar.gz'
sudo bash -c 'cp multichain-'$multichainVersion'*/multichain* /usr/local/bin/'

su -l $username -c  'multichain-util create '$chainname

# vote parameters
su -l $username -c "sed -ie 's/.*anyone-can-connect =.*\#/anyone-can-connect = true     #/g' /home/"$username"/.multichain/$chainname/params.dat"
su -l $username -c "sed -ie 's/.*anyone-can-send =.*\#/anyone-can-send = true     #/g' /home/"$username"/.multichain/$chainname/params.dat"
su -l $username -c "sed -ie 's/.*allow-p2sh-outputs =.*\#/allow-p2sh-outputs = false     #/g' /home/"$username"/.multichain/$chainname/params.dat"
su -l $username -c "sed -ie 's/.*allow-multisig-outputs =.*\#/allow-multisig-ouputs = false     #/g' /home/"$username"/.multichain/$chainname/params.dat"
su -l $username -c "sed -ie 's/.*setup-first-blocks =.*\#/setup-first-blocks = 10000     #/g' /home/"$username"/.multichain/$chainname/params.dat"
```

@[1-7](Download multichain.)
@[8-18](Parameters for voting being applied to blockchain.)

---

## How To Use
- [Go to Rock The Poll @fa[globe gp-download]](https://voteapp.gq)
- [Register](http://198.23.196.54/VoteApp/register.php)
  + [Sign In](http://198.23.196.54/VoteApp/login.php)
- [Review Candidates](http://198.23.196.54/VoteApp/ic_send_vote.php)
- [Submit Vote]
  + By Clicking<br>
<input type="reset" class="mb-xs mt-xs mr-xs btn btn-success" onclick="sendMetadataToAddress('txtMyAddress', 'txtToAddrSWM', 'txtMessageSWM', 'txtUnitsSWM', this, 'outputSWM');" value="Send">
 From The Vote App Daskboard.<br>
- [View Vote Confirmation](http://198.23.196.54:2750/chains)
---

### Questions?

<br>
<a href="">
@fa[twitter gp-contact](@rockthepoll)
</a><a href="">
@fa[github gp-contact](rockthepoll)
</a>

---?image=assets/image/gitpitch-audience.jpg

@title[Go Rock The Poll!]

### Big Thanks To The <a href="www.rockhall.com">Rock & Roll Hall of Fame</a>!
#### [Go Rock The Poll @fa[globe gp-download]](https://voteapp.gq)

