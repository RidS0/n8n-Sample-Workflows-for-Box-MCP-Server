# n8n-Sample-Workflows-for-Box-MCP-Server
n8n Sample Tasks for Box MCP Server

This set has sample n8n tasks for use with the Box Model Context Protocol (MCP) server. The tasks show how to make docs, get data from docs, & deal with claim tasks with Box & n8n gear.

What's In Here

doc-gen-claim-gen/
Make docs for claim tasks with Box DocGen & test data.
Box DocGen Claim Gen.json: n8n task to make claim docs.
sample-data/claim_doc_template.docx: Doc template for claims.
sample-data/claim_data.json: Test claim data.

better-data-get/
Get more data from Box files.
Better Data Get.json: n8n task to get data.

claim-demo/
Demo task for claims.
Claim Demo None.json: n8n task for claims (no help).

easy-box-mcp-agent/
Easy Box MCP agent task.
Easy Box MCP Agent.json: n8n task for Box MCP agent tie-up.

Need To Rule

n8n set & on.
Get to Box MCP server & Box count.
Put the .json tasks into n8n.


Put the .json file you want into your n8n.
Set Box counts & MCP server tips as needed.
Run the task to auto make docs, get data, or deal with claims.
