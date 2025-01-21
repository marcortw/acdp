# What's this?
This repository was part of my M.Sc. in SW Engineering at the University of Oxford in 2016. It contains the dissertation itself.

It's a draft of a language and protocol to propagate communication demands in TCP/IP networks.

The protocol, which has been termed ACDP (Application Communication Demands Protocol), consists of two main parts. The internal domain-specific language is based on a formal description of JSON documents. The second part of ACDP is concerned with the distribution of such ACDP documents or messages. It describes the basic roles of a “Submitter” and a “Receiver” and a way to transmit messages between them. A multi-step process using two unicast and one multicast distribution mechanisms ensures that most of the common deployment scenarios are supported with ACDP. Proof of concept libraries were written for the Submitter and Receiver roles and successfully tested. The test clearly demonstrates that ACDP provides sufficient information to execute the tasks it is aiming for. Wide use of this protocol takes a lot of time and can only be achieved if it will be openly discussed and improved.

# STATUS: ARCHIVED
It never really took off, but it was a fun exercise, so I'll leave it here for anyone who might find it useful :)
