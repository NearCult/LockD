# LockD

Welcome buddy lets setup LockD<br/>
Note : **suggested to use gitbash terminal or wsl**

### clone the repo
```git
git clone git@github.com:NearCult/LockD.git
```

### move into project directory
```bash
cd LockD
```

### run shell script
```bash
./setup.sh
```

### Install Dependency - Do it only from root
```bash
# for frontend
pnpm add <Package-Name> --filter ./apps/lockd-app/react-src

# for backend
pnpm add <Package-Name> --filter backend
```

### To Run Frontend
```bash
cd apps/lockd-app
neu run
```

### To Run backend
```bash
cd backend
pnpm run dev
```