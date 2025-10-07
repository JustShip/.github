# JustShip

**Ship your SaaS idea fast**

JustShip is a production-ready template designed to help you deploy your SaaS or idea as quickly as possible. Stop wasting time on boilerplate setup and focus on building your product.

## What's Included

- **Frontend**: Modern Next.js application with best practices
- **Backend**: Python/Django REST API with authentication and database setup
- **Infrastructure**: Ansible playbook for automated VPS deployment

## Quick Start

### Prerequisites

- Node.js 18+ (for frontend)
- Python 3.10+ (for backend)
- Ansible (for deployment)

### Local Development

1. Clone the repository
```bash
git clone https://github.com/yourusername/justship.git
cd justship
```

2. Start the frontend
```bash
cd frontend
npm install
npm run dev
```

3. Start the backend
```bash
cd backend
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

## Deployment

The included Ansible playbook automates VPS setup and deployment:

```bash
cd playbook
ansible-playbook -i inventory deploy.yml
```

## Project Structure

```
justship/
├── frontend/       # Next.js application
├── backend/        # Django REST API
└── playbook/       # Ansible deployment scripts
```

## Features

- 🚀 Fast setup and deployment
- 🔐 Built-in authentication
- 📦 Database migrations ready
- 🎨 Modern UI components
- ☁️ VPS deployment automation
- 🔧 Production-ready configuration

## License

Private

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
