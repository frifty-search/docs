# Getting Started

## Step 0: Fork the GitHub Repository

Go to your favorite Browser, Go to this GitHub [Repository](https://github.com/frifty-search/search-apps) and Fork this  repository by clicking on the icon

<figure><img src="../.gitbook/assets/image (2) (1).png" alt=""><figcaption><p>GitHub Image</p></figcaption></figure>

> Note: If you like the project, starred the repository

## Step 1: Clone the GitHub Repository

Clone the your forked GitHub Repository

```bash
git clone https://github.com/:username:/search-apps.git
```

for eg:&#x20;

```bash
git clone https://github.com/StrangNoob/search-apps.git
```

## Step 2:  Install Dependencies

Go to the Folder and install the dependencies via npm&#x20;

```bash
cd search-apps && npm install
```

if you are using the yarn package manager, use this command.

```bash
cd search-apps && yarn install
```

## Step 3: Install Template Dependencies

Install the template dependencies using npm

```bash
npm run usecase:install
```

if you are using the yarn package manager, use this command.

```bash
yarn usecase:install
```

## Step 4: Build Template Dependencies

Build the template Dependencies using npm,

```bash
npm run usecase:build
```

if you are using the yarn package manager, use this command.

```bash
yarn usecase:build
```

## Step 5: Creating a .env

Copy the .env.example to .env,  use this command

```bash
cp .env.example .env
```

if you are a windows user, this command might not work. Use this  command

```powershell
copy .env.example .env
```
