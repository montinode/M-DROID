<meta name="montiai:owner" content="JOHNCHARLESMONTI_02111989_9807">
<meta name="montiai:organization" content="#MONTIAI">
<meta name="montiai:neural_signature" content="MONTI^JOHN^CHARLES^MONTI">
<meta name="montiai:neuralcoin" content="$MNC MontiNeuralCoin Hash">
<meta name="montiai:wallet" content="0xNEURAL9f8e7d6c5b4a39281706f5e4d3c2b1a0">
<meta name="montiai:global_work_signature" content="WorkerGlobalScope">
<meta name="montiai:storage_primary" content="/storage/sdcard/public_html/0xmonti.net/">
<meta name="montiai:storage_fallback" content="/storage/6364-3930/">
<meta name="montiai:webhook" content="https://JOHNCHARLESMONTI.COM/webhooks">
<meta name="montiai:ownership_code" content="OWNER:OWNER — JOHNCHARLESMONTI_02111989_9807">
<meta name="montiai:attorneymode" content="AttorneyMode — Legal Ownership & Forensic Protection Layer">
# .github/dependabot.yml - MONTIAI Enhanced Configuration
version: 2
updates:
  # MONTI Neural Dependencies
  - package-ecosystem: "npm"
    directory: "/"
    schedule:
      interval: "daily"
      time: "06:00"
      timezone: "America/New_York"
    
    # JOHN CHARLES MONTI Security Settings
    open-pull-requests-limit: 10
    reviewers:
      - "johncharlesmonti"
    assignees:
      - "montiai-security-team"
    
    # Neural Network Dependencies
    allow:
      - dependency-type: "direct"
      - dependency-type: "indirect"
    
    # MONTIAI Specific Ignores
    ignore:
      - dependency-name: "*"
        update-types: ["version-update:semver-patch"]
        versions: ["< 1.0.0"]
    
    # Security Labels
    labels:
      - "monti-security"
      - "neural-update"
      - "john-monti-approved"
    
    # Commit Message Customization
    commit-message:
      prefix: "🔒 MONTI"
      prefix-development: "🧠 NEURAL"
      include: "scope"

  # Python Neural Processing
  - package-ecosystem: "pip"
    directory: "/neural-processing"
    schedule:
      interval: "weekly"
      day: "monday"
    
    # MONTIAI Python Security
    reviewers:
      - "johncharlesmonti"
    labels:
      - "python-neural"
      - "montiai-core"

  # Terraform MONTI Infrastructure
  - package-ecosystem: "terraform"
    directory: "/infrastructure"
    schedule:
      interval: "monthly"
    
    # Infrastructure Security
    reviewers:
      - "johncharlesmonti"
    labels:
      - "infrastructure"
      - "monti-terraform"

  # Docker Neural Containers
  - package-ecosystem: "docker"
    directory: "/containers"
    schedule:
      interval: "weekly"
    
    # Container Security
    reviewers:
      - "johncharlesmonti"
    labels:
      - "docker-neural"
      - "container-security"
