# About

My [Semaphore UI](https://github.com/semaphoreui/semaphore) playground.

# Usage

Install docker and docker compose.

Start the environment:

```bash
docker compose up --detach
```

Access the Semaphore UI as `admin:admin` at:

http://localhost:3000

Destroy the environment:

```bash
docker compose down --timeout=0 --remove-orphans --volumes
```

# Alternatives

* [Ansible AWX](https://github.com/ansible/awx)
  * [My AWS Playground](https://github.com/rgl/awx-vagrant)
