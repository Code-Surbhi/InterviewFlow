# InterviewFlow 🚀

A serverless coding practice tracker built on AWS.

## What It Does

- Track coding practice sessions (topic, difficulty, time spent)
- Generate personalized study recommendations
- Fully serverless — runs on AWS Lambda + DynamoDB

## Architecture

- **Frontend:** Static HTML/JS hosted on S3
- **API:** AWS API Gateway HTTP API
- **Logic:** AWS Lambda (Node.js)
- **Database:** AWS DynamoDB

## Tech Stack

- AWS SAM (Infrastructure as Code)
- AWS Lambda
- AWS DynamoDB
- AWS S3 Static Hosting
- AWS API Gateway

## Progress

- [x] Day 1: Project setup ✅
- [x] Day 2: Backend APIs — Lambda functions written and validated ✅
- [ ] Day 3: DynamoDB + First deployment to AWS
- [ ] Day 4: Frontend
- [ ] Day 5: Recommendation engine
- [ ] Day 6: Security + monitoring
- [ ] Day 7: Final deployment

## What's Built So Far

### Backend (Day 2)

- ✅ SAM template with API Gateway, Lambda, DynamoDB
- ✅ `createSession` Lambda with validation
- ✅ `listSessions` Lambda with stats aggregation
- ✅ Local test events ready for deployment testing

## Author

Built as a portfolio project — 7-day serverless MVP challenge.
