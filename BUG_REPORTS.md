# Sample Bug Reports

| Title | Environment | Steps to Reproduce | Expected Result | Actual Result | Notes |
|-------|------------|-----------------|----------------|---------------|-------|
| Order created with wrong quantity | Web platform, Chrome latest version, test environment | 1. Open order form, 2. Enter valid data, 3. Submit order | Order created with correct quantity | Quantity differs | Issue reproducible consistently, logs attached |
| Login fails for valid credentials | Web platform, Firefox latest version | 1. Open login page, 2. Enter valid username/password, 3. Click submit | Successful login | Error 500 returned | Issue occurs intermittently |
| Dashboard does not refresh after transaction | Web platform, Safari latest version | 1. Perform transaction, 2. Check dashboard | Dashboard updates automatically | Values remain old until manual refresh | Issue reproducible consistently |
