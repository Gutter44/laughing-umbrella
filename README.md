# AI Opportunity Agent

The AI Opportunity Agent is designed to help **Humbled Beginnings Unlimited LLC** search, filter, score, analyze, report, and alert on government contract and grant opportunities. This repository uses cutting-edge AI technology alongside thoughtful business logic to streamline opportunity management.

## Features
- **AI Integration**: Analyze opportunities and extract insights using LLMs.
- **Opportunity Scoring**: Prioritize opportunities using a customizable scoring algorithm.
- **Reports & Alerts**: Generate detailed reports and receive alerts for high-priority opportunities.
- **API Integrations**: Seamless connection with SAM.gov, Grants.gov, and more.
- **Dashboard**: Manage opportunities, reports, alerts, and settings via an intuitive UI.

## Repository Structure
```plaintext
/ai-opportunity-agent/
├── /docs/                 # Detailed Documentation
├── /public/               # Static Assets
├── /src/                  # Source Files
│   ├── /app/              # Next.js App Router (UI Pages & API Routes)
│   ├── /components/       # Reusable UI Components
│   ├── /lib/              # Core Logic, Services, Utilities
│   ├── /hooks/            # React Hooks
│   ├── /middleware/       # Next.js Middleware
│   └── /styles/           # Global CSS and style config
├── /prisma/               # Prisma ORM
├── /scripts/              # Utility Scripts
├── /tests/                # Automated Tests
├── .env.example           # Example environment variables
├── .gitignore             # Git ignore file
├── README.md              # Project overview and setup instructions
└── ...
```

## Development Setup
1. **Clone the repository**:
   ```bash
   git clone https://github.com/Gutter44/ai-opportunity-agent.git
   cd ai-opportunity-agent
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Set up environment variables**:
   - Copy `.env.example` to `.env.local`.
   - Fill in required values, such as API keys and database connection strings.

4. **Set up the database**:
   ```bash
   npx prisma migrate dev
   npm run seed
   ```

5. **Run the development server**:
   ```bash
   npm run dev
   ```

6. **Run tests**:
   ```bash
   npm test
   ```

## Deployment
This project is optimized for deployment on **Vercel**:
1. Create a new project on Vercel and link it to this repository.
2. Set the environment variables in the Vercel dashboard.
3. Trigger a deployment:
   ```bash
   vercel deploy
   ```

## Contributing
We welcome contributions! Please open issues or submit pull requests for improvements or bug fixes.

## License
This project is licensed under the [MIT License](LICENSE).
