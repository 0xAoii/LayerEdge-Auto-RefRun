# LayerEdge-Auto-RefRun<h1>
LayerEdge Auto Ref + Run

Disclaimer: This program may cause your account to be tagged as sybil.
I recommend using a dummy or test account.
Thanks!

website : https://dashboard.layeredge.io/
 #
<h2>Prerequisites</h2>

VPS - Virtual Private Server

Node.js installed on your machine
#
<h2>Install</h2>

1. Prerequisites for NPM

```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.0/install.sh | bash
```

```
echo 'export NVM_DIR="$HOME/.nvm"' >> $HOME/.bash_profile
echo '[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"  # This loads nvm' >> $HOME/.bash_profile
echo '[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"  # This loads nvm bash_completion' >> $HOME/.bash_profile

source $HOME/.bash_profile
```

```
nvm install --lts
```

2. Clone repository
```
   git clone https://github.com/0xAoii/LayerEdge-Auto-RefRun.git
```
```
   cd LayerEdge-Auto-RefRun
```

4. Create Screen
```
   Screen -S "screen-name"
```
5. Install required dependencies
```
   npm install
```
6. Auto Ref and Create Wallets
```
   npm run autoref
```
Input desired number of referrals and wait for the process to complete
input your Referral Code (e.g. asecedscs)
e.g 10 wallets

7. Run Script to Run all Nodes (After wallets created)
```
   npm run start
```
