# intergraph
Thin, standardized, low-level python interface to various graph databases.

This is a mono-repository for multiple variants of this library,  
currently available for Neo4j version 4 and version 5.  
In principle, it could be ported to other graph databases, such as MemGraph or AWS Neptune.  

A spinoff of the NeoAccess library.

    HISTORY and AUTHORS:
        (For change log, see https://brainannex.org/history)
                
        - Intergraph (this library) is a 2025 spinoff of NeoAccess, namely its database-dependent part.
                Different versions of Intergraph exist to interface to different graph databases and
                their different major versions.
        
        - NeoAccess is a fork of NeoInterface;
                NeoAccess was created, and is being maintained, by Julian West,
                primarily in the context of the BrainAnnex.org open-source project.
                It started out in late 2021.

        - NeoInterface (the parent library)
                was co-authored by Alexey Kuznetsov and Julian West in 2021,
                and is maintained by GSK pharmaceuticals
                under an Apache License 2.0 (https://github.com/GSK-Biostatistics/neointerface).
                NeoInterface is in part based on the earlier library Neo4jLiaison,
                as well as on a library developed by Alexey Kuznetsov.

        - Neo4jLiaison, an ancestor library now obsolete, was authored by Julian West in 2020
                (https://github.com/BrainAnnex/neo4j-liaison)

