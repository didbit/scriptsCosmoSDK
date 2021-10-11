# ReStaking script - auto claiming and delegating rewards for Rizon Network

1. Download the script from my repository:

```bash
wget https://raw.githubusercontent.com/didbit/scriptsCosmoSDK/main/restakingRizon.sh
```

2. Give the permissions to this file:

```bash
chmod +x restakingRizon.sh
```

3. Edit this script with your credentials -> change these parameters: DELEGATOR='Your delegator address' ;
VALIDATOR='Your validator address' ;
PASWD='pass phrase from cli' ;
DELAY=36000 #in secs - how often restart the script ;
ACC_NAME=YourWalleName 
 
 ```bash
nano restakingRizon.sh
```
4. Open the screen or tmux session:
 
 ```bash
# tmux new-session -s rizonscript
```
5. Run auto claiming and delegating rewards:

 ```bash
bash restakingRizon.sh
```
6. Enjoy it :)

```bash
