# cfengine3
CFEngine Promises

iptables.cf - Update iptables rules with static rules in a dynamically updated
running iptables rule-set. This way, you don't have to flush any existing
rules, for example rules that are created and in use by docker or VM networks.
