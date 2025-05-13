## GitHub Workflow

The project includes an automated workflow that:

1. Triggers on pushes to the main branch
2. Sets up the necessary Git and Node.js environment
3. Automatically merges changes to specific branches. For this example:
   - store/store1
   - store/store2
4. Handles merge conflicts with appropriate error logging
5. Implements a 1-minute delay between branch merges

## Prerequisites

- Node.js 16.x
- Git
- GitHub repository with appropriate permissions

## Setup

1. Clone the repository:

   ```bash
   git clone [repository-url]
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Configure GitHub Actions:
   - Ensure the repository has the necessary permissions
   - Verify the workflow file is in the correct location (.github/workflows/)

## Development

The project uses React/Next.js for the frontend. To start development:

1. Run the development server:

   ```bash
   npm run dev
   ```

2. Open [http://localhost:3000](http://localhost:3000) in your browser

## Branch Management

The project uses the following branch structure:

- `main`: Primary development branch
- `store/store1`: Store-specific branch
- `store/store2`: Store-specific branch

## Contributing

1. Create a new branch from `main`
2. Make your changes
3. Submit a pull request to `main`
4. The automated workflow will handle the merges to store branches

## Support

Contact me at maria.lovelle.camacho@gmail.com
