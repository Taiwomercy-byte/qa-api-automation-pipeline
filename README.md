# qa-api-automation-pipeline

![API Tests](https://github.com/Taiwomercy-byte/qa-api-automation-pipeline/actions/workflows/ci-tests.yml/badge.svg)

# Test Plan for API Automation Project

# API: https://jsonplaceholder.typicode.com
# Endpoints & Test Cases :
# 1. GET /posts/1 - verify status code is 200 and "id" == 1
# 2. POST /posts - verify status 201 and response contains same data sent
# 3. PUT /posts/1 - verify status 200 and response shows updated data
# 4. DELETE /posts/1 - verify status 200
# 5. GET /comments?postId=1 - verify status 200 and list length > 0
