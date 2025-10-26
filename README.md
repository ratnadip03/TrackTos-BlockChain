# ========================================
# QUICK GITHUB REPOSITORY SETUP
# ========================================
# Run these commands in PowerShell/Terminal

# Navigate to your project
cd C:\Users\Ramchandra\Desktop\tracktots_modern

# Initialize Git (if not already done)
git init

# Create .gitignore file
echo "node_modules/" > .gitignore
echo ".env" >> .gitignore
echo "build/" >> .gitignore
echo "dist/" >> .gitignore
echo ".DS_Store" >> .gitignore
echo "*.log" >> .gitignore
echo "frontend/build/" >> .gitignore
echo "backend/node_modules/" >> .gitignore
echo "frontend/node_modules/" >> .gitignore

# Create .env.example files for backend
cd backend
echo "PORT=8080" > .env.example
echo "STELLAR_SECRET_KEY=SXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX" >> .env.example
echo "STELLAR_DESTINATION=GXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX" >> .env.example

# Create .env.example files for frontend
cd ../frontend
echo "REACT_APP_API_URL=http://localhost:8080" > .env.example
echo "REACT_APP_GOOGLE_MAPS_KEY=AIzaXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX" >> .env.example

# Go back to root
cd ..

# Create LICENSE file
echo "MIT License" > LICENSE
echo "" >> LICENSE
echo "Copyright (c) 2025 [Your Name]" >> LICENSE
echo "" >> LICENSE
echo "Permission is hereby granted, free of charge, to any person obtaining a copy" >> LICENSE
echo "of this software and associated documentation files (the \"Software\"), to deal" >> LICENSE
echo "in the Software without restriction, including without limitation the rights" >> LICENSE
echo "to use, copy, modify, merge, publish, distribute, sublicense, and/or sell" >> LICENSE
echo "copies of the Software, and to permit persons to whom the Software is" >> LICENSE
echo "furnished to do so, subject to the following conditions:" >> LICENSE
echo "" >> LICENSE
echo "The above copyright notice and this permission notice shall be included in all" >> LICENSE
echo "copies or substantial portions of the Software." >> LICENSE
echo "" >> LICENSE
echo "THE SOFTWARE IS PROVIDED \"AS IS\", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR" >> LICENSE
echo "IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY," >> LICENSE
echo "FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE" >> LICENSE
echo "AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER" >> LICENSE
echo "LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM," >> LICENSE
echo "OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE" >> LICENSE
echo "SOFTWARE." >> LICENSE

# Add all files to git
git add .

# Create initial commit
git commit -m "Initial commit: Emergency IoT Monitoring System with Blockchain"

# ========================================
# NOW GO TO GITHUB.COM AND:
# 1. Click "New Repository"
# 2. Name it: emergency-iot-monitor
# 3. Don't initialize with README
# 4. Click "Create repository"
# 5. Copy the repository URL
# ========================================

# Then run these commands (replace YOUR_USERNAME and YOUR_REPO):
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git branch -M main
git push -u origin main

# ========================================
# DONE! Your repo is live on GitHub! 🎉
# ========================================

# Optional: Add topics/tags on GitHub:
# iot, esp32, blockchain, stellar, react, nodejs, health-monitoring, emergency-system
