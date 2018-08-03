In mathematics and computer science, a directed acyclic graph (DAG) is a finite directed graph with no directed cycles. Due to the excellent characteristics brought by the unique topology, it is often used to deal with dynamic programming, finding shortest paths, data compression, etc.

As the latest distributed ledger technology, DAG can be used to solve the scalability problem of traditional blockchain. Traditional blockchain is technically a DAG too, with the added restriction that there is a strict linear ordering of all items in a sequence. The strict sequencing in a blockchain directly causes or exacerbates the worst scaling issues we are seeing today. Because the structure of a DAGs isn’t as strict as a blockchain, the items can be shared and processed individually in a messier, out of order fashion. The less strictly ordered, realtime, global co-ordination that we require, the easier it is to scale up the network. DAGs are an elegant generalisation of blockchains, for the most part.

DAGX 2.0 is a new generation commercial value exchange network based on DAG technology. It will focus on dramatically improving the processing efficiency and providing highly scalable smart contracts. Based on the current DAGX 1.0, we will gradually research and implement the following improvements:

1. Optimize the P2P network communication component: replace the P2P network communication component in the existing code, and use the libp2p library developed by Protocol Labs to get better transmission performance, NAT transverse capability and encryption connections;
2. Optimize the ledger data storage component: the DAG technology's performance is strongly depends on the computing capability of graph operations. Existing component cann't support large-scale graph operations. According to the requirements of graph operations and different node types, we'll use suitable graph database to get better processing performance;
3. Propose a new witness consensus mechanism: at present, the witness consensus algorithm is too centralized and lacks incentive mechanism. We will introduce a new witness mechanism by voting new witness in a pool of witnesses;
4. Support Turing complete smart contract: besides the existing scripted non-turing complete smart contract, we'll introduce a new secure computing virtual container to support Turing's complete smart contract.

With the optimization of the above technologies, we will form a new generation of DAGX underlying architecture to serve the applications and extensions better.

![](http://oc7urqs4c.bkt.clouddn.com/2018-08-03-DAGX_arch_en.png)

As an emerging distributed ledger technology, DAG is still in the stage of rapid development and innovation. DAGX 2.0 will actively promote the development and application of DAG technology to build a more secure and efficient value exchange network.