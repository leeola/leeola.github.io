+++
title = "Resume"
template = "resume.html"

[[extra.contact]]
icon = "fa-solid fa-envelope"
text = "leeres@fastmail.com"
url = "mailto:leegit@fastmail.com"

[[extra.contact]]
icon = "fa-solid fa-phone"
text = "541-579-4680"

[[extra.contact]]
icon = "fa-brands fa-github"
text = "Github"
url = "https://github.com/leeola"

[[extra.contact]]
icon = "fa-brands fa-linkedin"
text = "LinkedIn"
url = "https://www.linkedin.com/in/lee-olayvar-071287191/"

[extra]
skills = [
  ["Rust", "Go", "JavaScript", "Python", "SQL"],
  ["Tokio", "React", "OpenAPI"], 
  ["Git", "Docker", "Kubernetes", "S3", "Linux", "MySQL", "Postgres"],
]

[[extra.experiences]]
title = "Senior Backend Engineer"
company = "ShowSeeker"
company_description = "Cloud-based advertising order management system for media proposals"
location = "Remote & Tacoma, WA"
start_date = "2016"
end_date = "present"
roles = [
  { title = "Senior Data Engineer", start_date = "2020", end_date = "present", details = [
    "Built data processing platform in Rust for Nielsen local viewership surveys. Processing ~500GiB of survey data",
    "Scaled the viewership data processing implementation to handle many new data sources totaling ~2.5PiB of survey data while maintaining fast query response times to end users",
    "Migrated viewership data processing to a content addressed system for data observability and integrity"
  ]},
  { title = "Backend Data Engineer", start_date = "2017", end_date = "2020", details = [
    "Migrated viewership system from Go to Rust for better performance and stronger type safety",
    "Implemented several new Rust based backend services for new Pilot platform modules",
    "Started company wide migration from Python and Go to Rust",
    "Mentored team members on Rust adoption and best practices",
  ]},
  { title = "Backend Engineer", start_date = "2016", end_date = "2017", details = [
    "Worked in Python on core backend infrastructure",
    "Architected and implemented viewership analytics system for ShowSeeker Plus platform in Golang",
  ]}
]

[[extra.experiences]]
title = "Software Engineer"
company = "Koding"
company_description = "Cloud-based development environment and collaboration platform"
location = "Remote & San Francisco, CA"
start_date = "2013"
end_date = "2016"
roles = [
  { title = "Backend Engineer", start_date = "2014", end_date = "2016", details = [
    "Developed core backend infrastructure in Golang",
    "Led development of Koding's Klient, a local-to-remote synchronization infrastructure and client",
    "Contributed numerous PRs to <a href=\"https://github.com/koding/koding/pulls?q=is%3Apr+author%3Aleeola+is%3Aclosed\" target=\"_blank\">Koding core platform</a>"
  ]},
  { title = "Full Stack Developer", start_date = "2013", end_date = "2014", details = [
    "Created <a href=\"https://github.com/koding/kpm-scripts\" target=\"_blank\">KPM (Koding Package Manager)</a> and created, updated and managed the KPM packages"
  ]},
  { title = "Community Manager", start_date = "2013", end_date = "2013", details = [
    "Supporting a developer oriented user community",
    "Developed the <a href=\"https://github.com/leeola/kdlearn\" target=\"_blank\">KDLearn educational content</a> website"
  ]}
]

[[extra.experiences]]
title = "Customer Service Specialist"
company = "Washington Secretary of State"
company_description = "State government agency"
location = "Olympia, WA"
start_date = "2007"
end_date = "2012"
roles = [
  { title = "Customer Service Specialist II (CSS2)", start_date = "2009", end_date = "2012", details = [
    "Handled sensitive data including private health records and government retention records",
    "Implemented strict retention policies around government records",
  ]},
  { title = "Customer Service Specialist I (CSS1)", start_date = "2007", end_date = "2009", details = [
  ]}
]

[[extra.projects]]
title = "Fixity - Distributed Immutable Storage System"
company = "Open Source Project"
start_date = "2017"
end_date = "2023"
details = [
  "Designed and implemented an immutable content-addressable and CRDT (Conflict-free Replicated Data Types) based storage system",
  "Implemented rolling checksum probabilistic b-trees, for efficient immutable indexing and retrieval",
  "Explored pros and cons of several architectural designs and data structures for content addressed systems",
  "Project: <a href=\"https://github.com/leeola/fixity\" target=\"_blank\">github.com/leeola/fixity</a>",
]

+++

# Resume

This resume is built with Zola using structured frontmatter data.
