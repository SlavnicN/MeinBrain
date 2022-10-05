Tags: [[blockchain]] [[Solidity]] [[security]]
# Race Condition

a TX could be frontrunned and alter the intial goal of the TX, this happen between the creation
    of the TX and the actual execution of the TX on the blockchain
    => ERC20 and approuve are prone to that, make sure that the approuve is only done when the approver has 0 
        allowance