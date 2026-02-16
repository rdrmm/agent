# agent
rdRMM was conceived as an 'agentless' solution, living off the land using existing utilities and tools.
On the fence between elegance and chaos, the 'agent' is currently a:
1) Scheduled Task
2) Running every minute
3) As "System"
4) Calling an HTTPS endpoint
5) And executing the instructions returned

Seems simple enough, perhaps too simple, what's to stop a malicioius user from joining? What's to stop one from masqarading as another?

Perhaps an ssh client over ssh can help with some of the issues
