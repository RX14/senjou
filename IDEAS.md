- Work like homu: always test the exact commit we push
  - This requires serializing merges
  - Batch merges
    - But not excusively: we can rebase on master for a preliminary travis-style CI for a first pass, then batch together
      PRs for merge which have already passed traditional CI for homu-style CI
- Auto-squash fixup commits when rebasing on master
- Bot command for adding a reproducing example in an issue OP to a list of samples to test weekly to see if they get fixed
- Really nice web UI (read-only)
- Commands are excusively github comments
  - Don't spam github issues to make them hard to read though!
