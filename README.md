This was made following the Fireship Next 13 tutorial

# Setup

Create a new Next.js app: npx create-next-app@latest --ts

Download Pocketbase from pocketbase.io

Navigate to the unzipped directory cd pocketbase_0.7.9_darwin_arm64

Start Pocketbase: ./pocketbase serve

Open the Admin UI, create collection, and update security rules to allow read/write access.

Add experimental: { appDir: true } to next.config.js

