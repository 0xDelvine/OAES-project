# Welcome to our Online Examination Administration System

## Steps to Set Up the Project

### Step 1
On your terminal, type the following command to clone the repository:

```bash
git clone https://github.com/0xDelvine/OAES-project.git
```

Alternatively, you can download the zip file from this repository.

### Step 2
Navigate to the `backend` folder and install the dependencies:

```bash
cd backend
npm install
```

### Step 3
Navigate to the `frontend` folder and install the dependencies:

```bash
cd ../frontend
npm install
```

### Step 4
Install MongoDB on your system.

---

## Ukimaliza those steps, time to run the system!!!

### Step 1
Open **three terminals**:
- One for running `mongosh`
- One for running the backend
- One for running the frontend

### Step 2
On the **first terminal**, type:

```bash
mongosh
```

### Step 3
In the same terminal, create and switch to the database you want to use. For example:

```bash
use db
```

Replace `db` with the name of the database you want to create. This database will store information for the accounts (admin, lecturer, and student).

### Step 4
Switch to the **second terminal**, navigate to the `backend` folder, and run:

```bash
cd backend
npm run dev
```

### Step 5
Switch to the **third terminal**, navigate to the `frontend` folder, and run:

```bash
cd frontend
npm run start
```

Your application should now be running!
Mtume za kabej😌
```
