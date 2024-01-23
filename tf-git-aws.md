# working with github.com.bca-github-testing
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/github.com.bca-github-testing
ssh -T git@github.com

# goto repo you want to work with
git config user.name "bca-github-testing"
git config user.email "kuberhtoo1991@gmail.com"
# =====================================================

# working with github.com.bca-github-dev
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/github.com.bca-github-dev
ssh -T git@github.com

# goto repo you want to work with
git config user.name "bca-github-dev"
git config user.email "kuberhtoo.dev@gmail.com"
# =====================================================

# working with github.com.bca-github-prod
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/github.com.bca-github-prod
ssh -T git@github.com

# goto repo you want to work with
git config user.name "bca-github-prod"
git config user.email "kuberhtoo.prod@gmail.com"