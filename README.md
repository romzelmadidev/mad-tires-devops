# \# Mad Tires - Big Bike E-Commerce Platform

# 

# \## About

# Mad Tires is a premium big bike and performance tire e-commerce platform 

# built with Java 21. The platform features Redis caching for optimized 

# API response times.

# 

# \## Features

# \- Browse premium big bikes (CBR650R, ZX-6R, MT-09)

# \- Performance tire catalog (Pirelli, Michelin, Bridgestone)

# \- Redis-cached API endpoints for fast product retrieval

# \- Real-time performance metrics dashboard

# 

# \## Tech Stack

# \- Java 21 LTS

# \- HTTP Server (com.sun.net.httpserver)

# \- ConcurrentHashMap (Redis cache simulator)

# 

# \## API Endpoints

# | Endpoint | Description |

# |---|---|

# | `/api/products` | Uncached product listing (\~200ms) |

# | `/api/products/cached` | Cached product listing (\~1ms) |

# | `/api/metrics` | Live cache metrics |





\## Installation



1\. Clone the repository

&#x20;  ```bash

&#x20;  git clone https://github.com/romzelmadidev/mad-tires-devops.git

&#x20;  cd mad-tires-devops

