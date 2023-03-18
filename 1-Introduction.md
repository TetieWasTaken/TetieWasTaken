```zsh
find ~ -name "README.md" -empty # ~/TetieWasTaken/README.md
cd ~/TetieWasTaken
cat $(find . -type f -name "*.md" -not -name "README.md" | sort) > ./README.md
```

<!-- End of introduction-->
