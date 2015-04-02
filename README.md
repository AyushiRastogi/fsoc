# fsoc
Forking, and Sustainability of the Developer Community

We analyzed the influence of forking on the sustainability of the developer community for the years 2008-2012.
The data generated for this study is huge, so to help understanding we present data for one year, that is, 2008 

File forktype_2008 show fork tree of a project on pull request history and commit history
MF_Id: Repository ID of the master fork
PF_Id: Repository ID of the primary fork
SF_ID: Repository ID of the secondary fork
user_id: Developer who initiated the pull request
pull_request_id: Unique ID of the pull request initiated
merged: show the status of the pull request: 0 is not merged and 1 is merged

Master fork is at the root of the tree
Forks of master forks are termed as primary forks
Forks of primary forks are termed as secondary forks

Classification of forks on Pull request history or commit history
1. Forks which send pull requests to master forks are Endogenous Forks
2. Forks which send pull requests to primary forks are Exogenous Forks
3. Forks where source and destination are same are termed as Intra Forks
4. Forks with no pull request and commit counts are Internally Developed Forks
5. Forks with no pull request or commit history are Dormant Forks
_____________________________________________________________________________

File commithistoryofmf_2008 show developer community participation in the master fork
mf_id: Repository ID of the master fork
commmit_id: Unique ID of the commit
author_id: ID of the contributor of the code
committer_id: ID of the committer of the code
created_at: Timestamp of commit

File commithistoryofpf_2008 show developer community participation in the primary fork
mf_id: Repository ID of the master fork
pf_id: Repository ID of the primary fork
commmit_id: Unique ID of the commit
author_id: ID of the contributor of the code
committer_id: ID of the committer of the code
created_at: Timestamp of commit
