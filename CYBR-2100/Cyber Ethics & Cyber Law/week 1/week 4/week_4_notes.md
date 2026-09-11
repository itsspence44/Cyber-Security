# Code, Content, Data, AI & Vulnerability Disclosure

*Intellectual Property Foundations*
   Copyright · Patents · Trademarks · Trade Secrets



# The Four Pillars of Intellectual Property Law



**Copyright**

Protects original works of authorship — including software code,
documentation, and digital content. Rights arise automatically at creation. 

Does not require registration to exist, though registration enables certain
remedies.



**Patent**s
Protect inventions and novel processes. Require registration. In software, 

patents cover specific technical implementations, not general ideas. Must be
novel, non-obvious, and useful.




**Trademarks** 

Protect brand identifiers — names, logos, and marks that distinguish goods or
services. 

Relevant in cybersecurity when tools, products, or companies are
misrepresented or impersonated.

# Copyright and Software


Copyright in software source code arises the moment the code is written — no registration required

The copyright owner controls reproduction, distribution, modification, and derivative works

A developer retains copyright in code they write unless they are an employee (work made for hire) or have contractually assigned the
rights

Using someone else's code without a license is copyright infringement — regardless of whether the code is "publicly visible"

Modification of someone else's copyrighted code does not eliminate the copyright or the licensing obligations that apply to it

Documentation, tutorials, and README files are also copyrighted works — not freely reusable without license 

U.S. Copyright Office resource: copyright.gov — review for background on these principles



# Trade Secrets in Cybersecurity 

Proprietary Security Architecture

Network diagrams, security control designs, and incident response playbooks are trade secrets. 

Disclosure to competitors or posting publicly breaches confidentiality obligations.




# Software Licensing & Open Source 
*What licenses do · Why they matter · Public does not mean free* 


**What a Software License Does** 

A software license is the legal instrument through which copyright holders grant others permission to use, copy, modify, or distribute
their code. Without a license, the default rule is that no permissions are granted — all rights reserved by the author

A license may expand permissions (allow copying, modification, commercial use) or restrict them (require attribution, share -alike, non-
commercial only)

Licenses may impose conditions — obligations that must be met for the permissions to remain valid
Violating a license condition can expose an organization to copyright infringement liability

Even open-source licenses impose conditions — "open source" does not mean "no rules"

GitHub resource: docs.github.com/en/repositories — licensing a repository


**Common Open Source License Types** 


MIT License

Permissive — allows use, copy, modification, and distribution with minimal
restrictions. 
Requires only that the original copyright notice and license text be retained. 
 
One of the most widely used and business-friendly licenses.
Apache 2.0

Permissive — similar to MIT but also includes an express patent license grant.

Requires attribution and a NOTICE file if one exists. Commonly used in enterprise and cloud projects.


# GitHub Repository Investigation

**GitHub Repository Investigation** 

What the repository does — tool, script, framework, or utility

Whether a license file is present and what it is named

What the license permits use, modification, redistribution, commercial use


# Licensed vs. Unlicensed Repositories 

*Licensed Repositories* 

MIT or Apache 2.0 — usually organization-friendly with attribution

GPL — copyleft obligations attach to derivative works

Creative Commons — content licenses, not code licenses

Multiple licenses — different parts under different terms

License in root — easiest to find and verify

License referenced in README — check the actual file   





