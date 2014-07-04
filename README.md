git
===

https://about.gitlab.com/downloads/



error: RPC failed; result=22, HTTP code = 411 

error: RPC failed; result=22, HTTP code = 413 


调整nginx：

client_max_body_size 50m;



/var/opt/gitlab/postgresql/data/pg_hba.conf

/var/opt/gitlab/postgresql/data/postgresql.conf


# TYPE  DATABASE  USER  CIDR-ADDRESS  METHOD

local       db1      

host        db1,db2

hostssl     all

hostnossl





sudo -u gitlab-psql psql -d gitlabhq_production -p 5432


/var/opt/gitlab/git-data/gitlab-satellites/<user|group>/<repos>
