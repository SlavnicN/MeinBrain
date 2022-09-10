# 01/05/22
 - Troubleshouting Amixer
     - the only commande "amixer sset Master toggle" won't work. Apperently it's
         because I have PulseAudio install too and because it's a multiple setup.
         For that I need to add "amixer -D pulse sset Master toggle" 
     - alsamixer is a nice visual tool is mic problem apear 
     link: https://wiki.archlinux.org/title/PulseAudio/Troubleshooting#Output_stuck_muted_while_Master_is_toggled

# 15/06/22
 - use Pytezos for unittest and integration test, succeding in launching a local tezos node in a 
 docker container             

# 22/06/22
 - try to continue test integration, was blocked by the the superAdmin call that didn't match the admin address
 - try to make pack() work with alex but didn't succed
 - git stash how to use it -> Stashed wip in test integration

# 23/06/22
- Reading about foundry 
- simple test of the marketplace fixe price, but not working
- Foundry pro:                                                 
     - interesting stuff in Foundry, the cheatscode allow you to mess with a lot variable, block time, change storage at certain points
      - Fuzzing 
      - Write test in solidity 
      - Verbose              