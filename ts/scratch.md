CREATE TABLE public.sqlth_1_test (
t_stamp bigint NOT NULL,                                   
intvalue bigint,
floatvalue double precision,
datevalue timestamp without time zone,
tagid integer NOT NULL,
dataintegrity integer,
stringvalue character varying(255),
); 
 tagid | intvalue |    floatvalue     | stringvalue | datevalue | dataintegrity |    t_stamp                                                                                  
-------+----------+-------------------+-------------+-----------+---------------+---------------                                                                              
    12 |          | 99.47396102437466 |             |           |           192 | 1724587218445


------------------------------------------------------------------------------------------

select oid::regclass from pg_class where relfilenode = 56036;                                                                                                                                                                                                                                                                                                
reindex table _timescaledb_internal._hyper_1_43_chunk;    
