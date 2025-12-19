# API Automation

## Repo
GoREST API Portfolio (Postman + Newman)  
https://github.com/yltsmees/gorest-postman-newman-portfolio

## What this demonstrates
- Postman collection design with clear ordering and coverage
- Chained request flows using environment variables (IDs saved and reused)
- Newman CLI runs locally and in CI
- HTML reporting output

## Token safety
The exported environment file in the repo keeps the token empty on purpose.
You inject the token at runtime (local CLI or CI secret).

## What to review first
- Postman collection JSON
- Environment file that excludes token
- Newman execution and report output
- GitHub Actions workflow (CI run + artifacts)
