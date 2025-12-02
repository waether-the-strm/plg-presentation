# PLG Presentation

Presentation for LetsReg – Design, UX & Product-Led Growth.

## Setup

Install dependencies:

```bash
pnpm install
```

## Development

Start development server:

```bash
pnpm dev
```

The presentation will open automatically in your browser at `http://localhost:3000`.

## Build

Build for production:

```bash
pnpm build
```

Preview production build:

```bash
pnpm preview
```

## Deployment to Netlify

### Option 1: Netlify CLI

1. Install Netlify CLI:
```bash
npm install -g netlify-cli
```

2. Build the project:
```bash
pnpm build
```

3. Deploy:
```bash
netlify deploy --prod
```

### Option 2: Git-based deployment

1. Push your code to GitHub/GitLab/Bitbucket
2. Connect your repository to Netlify
3. Configure build settings:
   - **Build command:** `pnpm build`
   - **Publish directory:** `dist`
4. Deploy!

### Option 3: Drag & Drop

1. Build the project:
```bash
pnpm build
```

2. Go to [Netlify Drop](https://app.netlify.com/drop)
3. Drag and drop the `dist` folder

The site will be automatically deployed and you'll get a URL.

