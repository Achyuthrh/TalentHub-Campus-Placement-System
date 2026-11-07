
## Windows Setup

### 1. Clone the repository

```powershell
git clone https://github.com/YOUR_USERNAME/TalentHub-Campus-Placement-System.git
cd TalentHub-Campus-Placement-System
```

### 2. Create virtual environment

```powershell
python -m venv .venv
```

### 3. Activate environment

```powershell
.venv\Scripts\Activate.ps1
```

### 4. Install dependencies

```powershell
pip install -r requirements.txt
```

### 5. Run the application

```powershell
python -m uvicorn main:app --reload
```

### 6. Open the application

- Website: http://127.0.0.1:8000
- API Docs: http://127.0.0.1:8000/docs
- Health Check: http://127.0.0.1:8000/api/health
