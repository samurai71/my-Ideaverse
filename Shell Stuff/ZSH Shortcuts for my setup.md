## Git Workflow Aliases
### Push current branch to origin
alias **push**='git push origin $(git rev-parse --abbrev-ref HEAD)'
### Pull current branch with submodules
alias **pull**='git pull --recurse-submodules origin $(git rev-parse --abbrev-ref HEAD)'
### Show git status in short format
alias **s**="git status -s"
### Commit with message (usage: c "commit message")
alias **c**="git commit -m"
### Add all files and show status
alias **a**='git add . && git status -s'
### Show git log in compact graph format
alias **l**='git log --oneline --all --graph --decorate'
### Fetch and checkout branch (usage: gb branch-name)
alias **gb**='git fetch && git checkout '
### Revert changes to files (usage: undo file.txt)
alias **undo**='git checkout --'
### Hard reset to previous commit
alias **reset**='git reset --hard HEAD~1'
### Show what files would be cleaned (dry run)
alias **clean**='git clean -dnx'
### Create and checkout new branch
alias **branch**='git checkout -b'
### End-of-week commit workflow
alias **friday**='pull && git checkout -b "friday-$(date +%Y-%m-%d)" && git commit -a -m "[WIP] Latest changes from Friday $(date +%Y-%m-%d)" && push'
### Show diff for specific files
alias **changes**='git diff --'
### Abort current merge
alias **nomerge**='git merge --abort'

## Docker Compose Aliases (Updated to use new 'docker compose' syntax)
alias **dc**='sudo docker compose'  # Docker compose with sudo
alias **dcu**='sudo docker compose up'  # Start services
alias **dcb**='sudo docker compose up --build -d'  # Build and start services in detached mode
alias **dcd**='sudo docker compose down'  # Stop and remove containers
alias **dcc**='sudo docker compose down -v --remove-orphans'  # Stop containers, remove volumes and orphans
 
# NPM Aliases
alias **nr**='npm run'  # Run npm script (usage: nr script-name)
alias **nrs**='npm run start'  # Start development server
alias **nrb**='npm run build'  # Build project
alias **npi**='npm install'  # Install dependencies

# Docker Aliases
alias **dp**='sudo docker ps'  # List running containers

# System Aliases
#alias **ls**='ls -lah --color=auto'  # Enhanced ls with human-readable sizes and colors

# Aliases candidates
### Amend last commit
alias **amend**='git commit --amend'  
### Create fixup commit
alias **fixup**='git commit --fixup'  
### Interactive squash (usage: squash 3)
alias **squash**='git rebase -i HEAD~'  

# Advanced Docker Aliases
# List images
alias **di**='sudo docker images'  
# Remove image
alias **drmi**='sudo docker rmi'  
# List all containers (including stopped)
alias **dps**='sudo docker ps -a'  
# Show container logs (usage: dlog container-name)
alias **dlog**='sudo docker logs'  
# Follow container logs
alias **dlogf**='sudo docker logs -f'  
# Execute command in container
alias **dexec**='sudo docker exec -it'  
# Shell into container (usage: dsh container-name /bin/bash)
alias **dsh**='sudo docker exec -it'  
# Stop container
alias **dstop**='sudo docker stop'  
# Start container
alias **dstart**='sudo docker start'  
# Remove container
alias **drm**='sudo docker rm'  
# Remove unused containers, networks, images
alias **dprune**='sudo docker system prune -f'  
# Remove everything unused (including volumes)
alias **dprunea**='sudo docker system prune -af'  

# Docker Compose Extensions
# Show service logs
alias **dcl**='sudo docker compose logs'  
# Follow service logs
alias **dclf**='sudo docker compose logs -f'  
# Execute command in service
alias **dce**='sudo docker compose exec'  
# Restart services
alias **dcr**='sudo docker compose restart'  
# Pull latest images
alias **dcp**='sudo docker compose pull'  
# Show service status
alias **dcps**='sudo docker compose ps'  

# NPM Extensions
# Run tests
alias **nrt**='npm run test'  
# Run tests in watch mode
alias **nrtw**='npm run test:watch'  
# Run development server
alias **nrd**='npm run dev'  
# Run linter
alias **nrl**='npm run lint'  
# Run formatter
alias **nrf**='npm run format'  
# Clean install from package-lock
alias **npci**='npm ci'  
# Update packages
alias **npu**='npm update'  
# Check for outdated packages
alias **npo**='npm outdated'  
# Security audit
alias **npa**='npm audit'  
# Fix security issues
alias **npaf**='npm audit fix'  

# System and Navigation Aliases
# Go up one directory
#alias  ..='cd ..'  
# Go up two directories
#alias  ...='cd ../..'  
# Go up three directories
#alias  ....='cd ../../..'  
# Go to home directory
alias  **~**='cd ~'  
# List all files in long format
#alias **la**='ls -la'  
# List in long format
#alias **ll**='ls -l'  
# List by time (newest last)
#alias **lt**='ls -lart'  
# List by size
#alias **lsize**='ls -laSh'  
# Create directories with parents and verbose
alias **mkdir**='mkdir -pv'  
# Colorized grep
alias **grep**='grep --color=auto'  
# Colorized fgrep
alias **fgrep**='fgrep --color=auto'  
# Colorized egrep
alias **egrep**='egrep --color=auto'  
# Command history
alias **h**='history'  
# List active jobs
alias **j**='jobs -l'  
# Print PATH in readable format
alias **path**='echo -e ${PATH//:/\\n}'  
# Current time
alias **now**='date +"%T"'  
# Current date
alias **today**='date +"%d-%m-%Y"'  
alias **cls**='clear'
alias **pn**='pnpm'
alias **ls**='eza $eza_params'
alias **l**='eza --git-ignore $eza_params'
alias **ll**='eza --all --header --long $eza_params'
alias **llm**='eza --all --header --long --sort=modified $eza_params'
alias **la**='eza -lbhHigUmuSa'
alias **lx**='eza -lbhHigUmuSa@'
alias **lt**='eza --tree $eza_params'
alias **tree**='eza --tree $eza_params'
alias **learn**='cd learning-projects'
alias **dev**="cd dev-projects"


# File Operations

# Interactive and verbose copy
alias **cp**='cp -iv'  
# Interactive and verbose move
alias **mv**='mv -iv'  
# Interactive and verbose remove
alias **rm**='rm -iv'  
# Interactive and verbose link
alias **ln**='ln -iv'  
# Prevent chmod on root
alias **chmod**='chmod --preserve-root'  
# Prevent chown on root
alias **chown**='chown --preserve-root'  
  
# Network and System Info
# Show open ports
alias **ports**='netstat -tulanp'  
# Disk usage in human format
alias **diskusage**='df -h'  
# Memory info in human format
alias **meminfo**='free -h'  
# CPU information
alias **cpuinfo**='lscpu'  

# Process Management
# Process search (usage: psg process-name)
alias **psg**='ps aux | grep -v grep | grep -i -e VSZ -e'  
# Top CPU processes
alias **topcpu**='ps auxf | sort -nr -k 3 | head -10'  
# Top memory processes
alias **topmem**='ps auxf | sort -nr -k 4 | head -10'  

# Quick Edits (adjust based on your preferred editor)
# Edit and reload bashrc
#alias bashrc='nano ~/.bashrc && source ~/.bashrc'  
# Edit and reload zshrc
#alias zshrc='nano ~/.zshrc && source ~/.zshrc'  
# Edit hosts file
#alias hosts='sudo nano /etc/hosts'  

# Development Shortcuts
# Quick HTTP server
alias **serve**='python -m http.server'  
# Pretty print JSON
alias **jsonpp**='python -m json.tool'  
# URL encode
alias **urlencode**='python -c "import sys, urllib.parse as ul; print(ul.quote_plus(sys.argv[1]))"'  
# URL decode
alias **urldecode**='python -c "import sys, urllib.parse as ul; print(ul.unquote_plus(sys.argv[1]))"'  

# chezmoi shortcuts
alias **cms**='chezmoi-sync'
