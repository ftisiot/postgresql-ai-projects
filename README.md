# List of PostgreSQL® AI projects and resources

[<img src="https://wiki.postgresql.org/images/a/a4/PostgreSQL_logo.3colors.svg" align="right"  width="100">](https://www.postgresql.org/)

> A curated list of PostgreSQL® project including or addressing AI

This list includes projects, extensions or demos showcasing how to use PostgreSQL® in the AI landscape

## ➕ Extensions

* [pgvector](https://github.com/pgvector/pgvector): open-source vector similarity search for PostgreSQL. Includes vector storage and similarity search, as well as IVFFlat and HNSW indexing
* [pg_vectorize](https://github.com/tembo-io/pg_vectorize): open-source PostgreSQL extension that automates the transformation and orchestration of text to embeddings, allowing vector and semantic search on existing data with as little as two function calls.
* [postgresml](https://github.com/postgresml/postgresml): Generative AI and Simple ML with PostgreSQL. Perform Text classification, Translation, Summarization directly in SQL within the PostgreSQL database.
* [azure_ai](https://techcommunity.microsoft.com/t5/azure-database-for-postgresql/introducing-the-azure-ai-extension-to-azure-database-for/ba-p/3980291):  Enables you to integrate Azure AI services with your operational data
* [azure_local_ai](https://techcommunity.microsoft.com/t5/azure-database-for-postgresql/introducing-in-database-embedding-generation-for-azure-database/ba-p/4146265):  Enables you to generate embeddings within the PostgreSQL database.
* [pgai](https://github.com/timescale/pgai): Enables you to generate embeddings within the PostgreSQL database. Developed by Timescale
* [pgvectorscale](https://github.com/timescale/pgvectorscale): Works in conjunction with pgvector and adds the DiskANN indexing type. Developed by Timescale
* [google_ml_integration](https://cloud.google.com/alloydb/docs/ai): It provides the AI query engine feature, which includes functions for generating embeddings, semantic ranking, and capacity to invoke predictions from models.


## 💡 Applications

### 🤖 Bots

* [PostgresAI bot](https://postgres.ai/bot): a PostgreSQL expert bot, by [PostgresAI](https://twitter.com/postgres_ai)

### 📑 Text to SQL and SQL to Text

* [Text to SQL](https://www.eversql.com/text-to-sql/): auto-generate SQL queries from text for free by [EverSQL by Aiven](https://www.eversql.com/?utm_medium=organic&utm_source=ext_blog&utm_content=listpostgresai)
* [SQL to Text](https://www.eversql.com/sql-to-text/?utm_medium=organic&utm_source=ext_blog&utm_content=listpostgresai): explains in plain english what your SQL query does by [EverSQL by Aiven](https://www.eversql.com/?utm_medium=organic&utm_source=ext_blog&utm_content=listpostgresai)


### ⚡️ Query Optimizer

* [Aiven SQL Query Optimizer](https://aiven.io/tools/sql-query-optimizer?utm_medium=organic&utm_source=ext_blog&utm_content=listpostgresai): AI-driven query optimizer based on SQL and database metadata. Monitor your database and receive performance insights and improvement suggestions for free

### 🎛️ Configuration Tuning

* [~~Ottertune~~](https://ottertune.com/): ~~AI to optimize your Amazon RDS and Aurora database~~ Ottertune is no longer a company
* [DBTune](https://www.dbtune.com/): AI driven PostgreSQL configuration tuning engine

## ✏️ Content

### 👩‍💻Code examples

* 📝[Image recognition with Python, OpenCV, OpenAI CLIP and pgvector](https://aiven.io/developer/find-faces-with-pgvector) by [Francesco Tisiot](https://www.linkedin.com/in/francescotisiot)
* 📝[TensorFlow, PostgreSQL®, PGVector & Next.js: building a movie recommender](https://aiven.io/developer/building-a-movie-recommender) by [Olena Kutsenko](https://www.linkedin.com/in/olenakutsenko/)
* 📽️[TensorFlow, PostgreSQL®, PGVector & Next.js: building a movie recommender](https://youtu.be/ll2VjbGHO4E) by [Olena Kutsenko](https://www.linkedin.com/in/olenakutsenko/)
* 📽️[How I found my Pokémon cards thanks to Postgres: an AI Journey](https://www.youtube.com/watch?v=QofVrNDSby4) by [Matt Cornillon](https://www.linkedin.com/in/matt-cornillon/) at [pgconf.eu 2023](https://2023.pgconf.eu/)
* 📽️[PostgresML: How to Use AI Models and Machine Learning Algorithms in Your Database](https://www.youtube.com/watch?v=JTgl5GwrMu8) by Let's Talk Dev
* 📝[What's Postgres Got To Do With AI?](https://www.crunchydata.com/blog/whats-postgres-got-to-do-with-ai) by Crunchy Data
* 📝[Real-time text translation using the azure_ai extension in Azure Database for PostgreSQL](https://techcommunity.microsoft.com/t5/azure-database-for-postgresql/real-time-text-translation-using-the-azure-ai-extension-in-azure/ba-p/4081157) by [Denzil Ribeiro](https://techcommunity.microsoft.com/t5/user/viewprofilepage/user-id/218602)
* 📽️ [Creating a Board Game Chatbot with Postgres, AI, and RAG](https://www.youtube.com/watch?v=EXk08pYVykE) by [Matt Cornillon](https://www.linkedin.com/in/matt-cornillon/) at [pgconf.eu 2023](https://2024.pgconf.eu/)
* 📽️ [Full-Text-Search Explained from A to Z with French Food](https://www.youtube.com/watch?v=ypBM3rvAAiM) by [Matt Cornillon](https://www.linkedin.com/in/matt-cornillon/) at [pgDay Paris 2025](https://2024.pgconf.eu/)

### What's next

* 📽️[What's next in pgvector](https://www.youtube.com/watch?v=CzeTgNoHXN0)
* 📝[pgvector 0.5.0 feature highlight and howtos](https://jkatz05.com/post/postgres/pgvector-overview-0.5.0/) by [Jonathan Katz](https://www.linkedin.com/in/jonathan-katz-6495532/)
* 📝[An early look at HNSW performance with pgvector](https://jkatz05.com/post/postgres/pgvector-hnsw-performance/) by [Jonathan Katz](https://www.linkedin.com/in/jonathan-katz-6495532/)

### Presentation slides

* 🛝[Finding PostgreSQL’s fit in the AI space](https://ftisiot.net/talks/postgresql-fit-ai/) by [Francesco Tisiot](https://www.linkedin.com/in/francescotisiot)
* 🛝[How I found my Pokémon cards thanks to Postgres: an AI Journey](https://github.com/Matthieu68857/how-i-found-my-pokemon-cards-thanks-to-postgres-an-ai-journey) by [Matt Cornillon](https://www.linkedin.com/in/matt-cornillon/) at [pgconf.eu 2023](https://2023.pgconf.eu/)
* 🛝[Creating a Board Game Chatbot with Postgres, AI, and RAG](https://www.postgresql.eu/events/pgconfeu2024/sessions/session/5737/slides/581/Creating%20a%20Board%20Game%20Chatbot%20with%20Postgres,%20AI,%20and%20RAG%20-%20PGConf%20Europe%202024.pdf) by [Matt Cornillon](https://www.linkedin.com/in/matt-cornillon/) at [pgconf.eu 2023](https://2024.pgconf.eu/)
