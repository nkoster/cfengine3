# cfengine3
CFEngine Promises

iptables.cf - Update iptables without flushing: Update iptables with static
rules in dynamically updated running iptables rules. This way, you don't
have to flush any existing rules, for example rules that are created / in use
by docker or VM networks.
