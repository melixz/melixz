graph LR
  subgraph Python
    A[Python]
  end
  subgraph FastAPI
    B[FastAPI]
  end
  subgraph Docker
    C[Docker]
  end
  subgraph Redis
    D[Redis]
  end
  subgraph Django
    E[Django]
  end
  subgraph PostgreSQL
    F[PostgreSQL]
  end
  subgraph HTML5
    G[HTML5]
  end
  subgraph Git
    H[Git]
  end
  subgraph Google
    I[Google]
  end
  A --> B
  A --> E
  B --> C
  B --> D
  E --> C
  E --> F
  G --> H
  G --> I
