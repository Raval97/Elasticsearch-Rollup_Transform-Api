# Elasticsearch-Rollup_Transform-Api

Api for Rollup and Transform in Elasticsearch for Scala

Rollup Api contains:
/job/
    PUT /_rollup/job/<job_id>: Create a rollup job
    GET /_rollup/job: List rollup jobs
    GET /_rollup/job/<job_id>: Get rollup job details
    POST /_rollup/job/<job_id>/_start: Start a rollup job
    POST /_rollup/job/<job_id>/_stop: Stop a rollup job
    DELETE /_rollup/job/<job_id>: Delete a rollup job
/data/
    GET /_rollup/data/<index_pattern>/_rollup_caps: Get Rollup Capabilities
    GET /<index_name>/_rollup/data/: Get Rollup Index Capabilities
/<index_name>/
    GET /<index_name>/_rollup_search: Search rollup data


Transforms Api contains:
    Create transforms
    Delete transforms
    Get transforms
    Get transforms statistics
    Preview transforms
    Start transforms
    Stop transforms
    Update transforms

Examples of using:

For Rollup
![Image description](https://github.com/Raval97/Elasticsearch-Rollup_Transform-Api/tree/master/screens/Screenshot from 2020-08-20 13-48-49.png?raw=true)

For Transforms
![Image description](https://github.com/Raval97/Elasticsearch-Rollup_Transform-Api/tree/master/screens/Screenshot from 2020-08-20 13-49-59.png?raw=true)

