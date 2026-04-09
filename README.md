# Market and Customer Sentiment Dashboard

Sentiment analysis dashboard for Amazon DynamoDB and Amazon Keyspaces, aggregating data from Reddit, StackOverflow, G2, PeerSpot, LinkedIn, X, and community forums.

**[Live Demo](https://main.d1jng0r6vthxw5.amplifyapp.com)**

## What It Does

Aggregates and visualizes customer sentiment across multiple platforms for database products. Helps product teams understand market perception, feature requests, and pain points.

## Features

- Product switcher between DynamoDB and Keyspaces
- Top use cases distribution (interactive pie chart)
- Why customers choose each product (horizontal bar chart)
- Feature mentions with sentiment radar chart
- Pain points with severity classification
- Most requested features with status tracking
- Key takeaways with positive/negative/neutral insights
- Apache Cassandra GitHub trends (Keyspaces only)

## Tech Stack

React 18 | TypeScript | Recharts | Vite | Framer Motion

## Getting Started

```bash
npm install
npm run dev
```

Open http://localhost:5173

## Deployment

Deployed on AWS Amplify as a serverless static site with HTTPS and CDN.
