# Sheet2API

**Sheet2API** is a web application that allows users to upload Excel files (.xlsx) and processes the data for easy access and integration. Whether you're dealing with business data, inventory lists, or any other type of structured data, Sheet2API helps you transform your spreadsheets into a usable format.

## 🚀 Features

- **Upload Excel Files**: Drag and drop Excel files (.xlsx) or use the file picker to upload your spreadsheets
- **File Processing**: Once uploaded, the data is processed and can be used within your application
- **Storage**: Files are securely stored in Amazon S3, ensuring scalability and reliability
- **Next.js Backend**: The backend is built using Next.js, providing a robust and flexible server-side environment
- **Beautiful UI**: The frontend is designed using **Next.js** and **ShadCN UI**, creating a modern, responsive, and accessible user interface

## 🛠️ Tech Stack

### Frontend
- **Next.js**: A React framework used for server-side rendering and building static websites
- **ShadCN UI**: A component library used to design a beautiful, responsive, and accessible user interface

### Backend
- **Next.js Backend**: APIs are built using Next.js API routes to handle file uploads and data processing
- **Amazon S3**: All uploaded files are securely stored in Amazon S3, providing reliable and scalable cloud storage

## 💡 Getting Started

Follow these steps to get started with Sheet2API:

### 1. Clone the Repository

```bash
git clone https://github.com/Bhup-GitHUB/Sheet2API.git
cd Sheet2API
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Set Up Environment Variables

Create a `.env.local` file at the root of the project and add your AWS S3 credentials:

```ini
AWS_ACCESS_KEY_ID=your_aws_access_key_id
AWS_SECRET_ACCESS_KEY=your_aws_secret_access_key
AWS_BUCKET_NAME=your_bucket_name
AWS_REGION=your_aws_region
```

### 4. Run the Development Server

```bash
npm run dev
```

Visit `http://localhost:3000` to view the app.

## 🎨 Frontend Preview

The frontend is built using **Next.js** and **ShadCN UI**, creating a sleek and modern UI for seamless user interaction.

**Key Features:**
- **File Upload**: Drag and drop files or use the file picker
- **Modern UI**: Designed with accessibility and responsiveness in mind

## 📦 Deployment

### Deploying on Vercel

To deploy on Vercel, follow these steps:

1. Push your repository to GitHub or GitLab
2. Go to [Vercel Dashboard](https://vercel.com/dashboard)
3. Select **New Project**, then connect your GitHub/GitLab repository
4. Vercel will automatically detect the Next.js project and set up the deployment

### Deploying on AWS

1. Create an EC2 instance or use AWS Lambda for serverless deployment
2. Set up S3 bucket access and integrate it with your backend
3. Deploy the application using Docker or other suitable services

## 🛠️ How It Works

1. **User Uploads Excel File**: The user uploads an Excel file via the frontend. The file is sent to the backend using a POST request
2. **File Processing**: On the backend, the file is parsed and processed into a structured format
3. **Storing in S3**: The file is uploaded to Amazon S3, and a unique identifier is generated

## 📝 Contributing

We welcome contributions to **Sheet2API**! Here's how you can help:

1. Fork the repository
2. Create a new branch (`git checkout -b feature-xyz`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add feature xyz'`)
5. Push to your branch (`git push origin feature-xyz`)
6. Open a pull request

## 🤝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🔗 Contact

For any questions or suggestions, feel free to open an issue or contact the project owner directly via [GitHub](https://github.com/Bhup-GitHUB/Sheet2API).
