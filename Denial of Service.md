Tags: [[blockchain]] [[Solidity]] [[security]]

# Denial of Service

 when one contract call another passing through a loop, if the call fail during the loop
    can create a DoS
    - Auction contract: if someone outbid a auction, and the refund of the previous bid fail constantly
        it will block the auction
    - iteration through array for payback, if one fail in the loop every call fails 
    - attacker spam a contract to make some array bigger, needing more gas for some tx and eventually out of gas 
        for normal user