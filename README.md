# Snowflake
Here is a **step-by-step roadmap** to learn Snowflake for SQL and data-warehousing, distilled from the most recent and practical sources.  
It is split into **4 phases** so you can track progress whether you are a total beginner or already comfortable with SQL.

###  Phase 0 – Prerequisites (1-2 weeks)
| Goal | Resources & Actions |
|---|---|
| Pick up enough SQL | Follow the free **freeCodeCamp SQL course**  or any “SQL for Data Analysis” playlist. |
| Understand DWH basics | 30-min YouTube overviews on “What is a data warehouse / data lake / star schema”. |

### Phase 1 – Get Comfortable with Snowflake (Week 1-2)
| Milestone | Hands-on Tasks | Tips |
|---|---|---|
| Open a free trial account | 30-day + $400 credits  | Students can ask for 90 days . |
| Do the “Snowflake in 20 min” lab | Install SnowSQL, create DB + table, load CSV, query it . | Keep warehouse size = XS to save credits. |
| Learn the UI context | Set ROLE / WAREHOUSE / DB / SCHEMA drop-downs correctly . | Prevents 90 % of “object does not exist” errors. |

### Phase 2 – Core SQL & Modeling (Week 3-6)
| Skill | What to Practice | Check-List |
|---|---|---|
| Snowflake SQL flavour | Sample TPC-H data: SELECT, JOIN, CTE, window functions, COPY INTO . | Pay attention to “Query Profile” for cost. |
| Data loading | Load local CSV, JSON, Parquet; stages, file formats, error handling . | Turn on `ON_ERROR = 'CONTINUE'` for large files. |
| Basic modeling | Build a star schema (fact + dims) with the retail sample data . | Use `TRANSIENT` tables for dev work to save storage. |

### Phase 3 – ETL, Performance & Security (Week 7-10)
| Topic | Key Labs & Docs | Deliverable |
|---|---|---|
| ETL/ELT pipelines | Streams + Tasks, schedule with CRON; build a daily “orders” pipeline . | Version-control the DDL in Git. |
| Performance | Clustering keys, warehouse scaling, result-cache demo; compare query times . | Document “before vs after” metrics. |
| Security | RBAC, network policies, row-access + column masking on “salary” column . | Produce a shareable security matrix spreadsheet. |

### Phase 4 – Advanced & Portfolio (Week 11-20)
| Track | Choose Your Focus | Project Ideas |
|---|---|---|
| Data Engineering | Snowpark Python, Snowpipe, external functions | Build a Kaggle-to-Snowflake auto-loader with quality checks . |
| Analytics & BI | Connect Power-BI / Tableau, materialized views, data sharing | Create a multi-tenant dashboard with secure data sharing . |
| Certification | Snowflake “SnowPro Core” exam guide & practice questions | Book the exam after 2 full practice passes. |

### Example 5-Month Timeline (adjust to your pace)
| Month | Target |
|---|---|
| 1 | Finish Phases 0-1, comfortable writing SQL in Snowsight. |
| 2 | Complete Phase 2, upload & model at least 1 real data set. |
| 3 | Phase 3, pipelines run nightly, queries tuned, security applied. |
| 4 | Phase 4 specialization + 1 end-to-end project in Git. |
| 5 | Second project, polish portfolio, sit SnowPro or internal company assessment. |

###  Continuous Learning Habits
1. **Daily SQL**: 30 min on [https://www.snowflake.com/learn-tutorials](https://www.snowflake.com/learn-tutorials) .  
2. **Weekly project block**: 2 h adding features to your portfolio repo.  
3. **Community**: join [Snowflake Community](https://community.snowflake.com) & r/Snowflake for feedback .

Follow the phases sequentially, keep everything in a **Git repo + short README**, and you’ll have both the skills and the proof when employers or clients ask for Snowflake expertise.
