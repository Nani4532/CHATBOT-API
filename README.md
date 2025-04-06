## Running Locally

To run the Next.js AI Chatbot locally, you’ll need to use the environment variables defined in [`.env.example`](.env.example).

### 🔐 Environment Setup

1. Create a file named `.env.local` in the root of the project.
2. Copy contents from `.env.example` and fill in the required API keys or secret keys.

> ⚠️ **Important:** Never commit your `.env.local` file to version control. It contains sensitive credentials that could compromise your accounts.

---

### 🧱 Build and Run

Make sure you have `pnpm` installed. Then run:

```bash
pnpm install
pnpm build      # Creates the .next folder
pnpm dev        # Starts the development server
