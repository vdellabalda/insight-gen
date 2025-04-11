# insight-gen
LLM automated insight generation from databases.

A Big Data project to streamline the generation of insight from multi-table insight bases through use of LLMs.
High-level questions are generated based on a summarized description of the available datasets and deconstructed to simpler low-level questions with inclusion of database schemas. Low-level questions are answered through use of agentic text-to-SQL translation and subsequent query to extract necessary information from the database.
Answers are then summarized to provide the final insight answering the high-level question.
