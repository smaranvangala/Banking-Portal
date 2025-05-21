
##Introduction

Run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## <a name="tech-stack">⚙️ Tech Stack</a>

- Next.js
- TypeScript
- Appwrite
- Plaid
- Dwolla
- React Hook Form
- Zod
- TailwindCSS
- Chart.js
- ShadCN

## <a name="features">🔋 Features</a>

**Authentication**: An ultra-secure SSR authentication with proper validations and authorization

**Connect Banks**: Integrates with Plaid for multiple bank account linking

**Home Page**: Shows general overview of user account with total balance from all connected banks, recent transactions, money spent on different categories, etc

**My Banks**: Check the complete list of all connected banks with respective balances, account details

**Transaction History**: Includes pagination and filtering options for viewing transaction history of different banks

**Real-time Updates**: Reflects changes across all relevant pages upon connecting new bank accounts.

**Funds Transfer**: Allows users to transfer funds using Dwolla to other accounts with required fields and recipient bank ID.

**Prerequisites**

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

Set Up Environment Variables

Create a new file named .env in the root of your project and add the following content:

#NEXT
NEXT_PUBLIC_SITE_URL=  

#APPWRITE  
NEXT_PUBLIC_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1  
NEXT_PUBLIC_APPWRITE_PROJECT=  
APPWRITE_DATABASE_ID=  
APPWRITE_USER_COLLECTION_ID=  
APPWRITE_BANK_COLLECTION_ID=  
APPWRITE_TRANSACTION_COLLECTION_ID=  
APPWRITE_SECRET=  
  
#PLAID  
PLAID_CLIENT_ID=  
PLAID_SECRET=  
PLAID_ENV=  
PLAID_PRODUCTS=  
PLAID_COUNTRY_CODES=  

#DWOLLA  
DWOLLA_KEY=  
DWOLLA_SECRET=  
DWOLLA_BASE_URL=https://api-sandbox.dwolla.com  
DWOLLA_ENV=sandbox  

Replace the placeholder values with your actual respective account credentials. You can obtain these credentials by signing up on the Appwrite, Plaid and Dwolla

Running the Project
npm run dev
