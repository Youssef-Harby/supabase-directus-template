# supabase-directus-template
Perfect Compo to start your Headless CMS

<p align="center">
<img width="300" src="https://raw.githubusercontent.com/supabase/supabase/master/packages/common/assets/images/supabase-logo-wordmark--light.svg#gh-light-mode-only">
<img width="300" src="https://raw.githubusercontent.com/supabase/supabase/master/packages/common/assets/images/supabase-logo-wordmark--dark.svg#gh-dark-mode-only">
</p>
<h1 align="center">++++</h1>
<p align="center">
<img width="300" src="https://raw.githubusercontent.com/directus/directus/main/app/src/assets/logo-dark.svg#gh-light-mode-only">
<img width="300" src="https://raw.githubusercontent.com/directus/directus/main/app/src/assets/logo.svg#gh-dark-mode-only">
</p>

- https://supabase.com/docs/guides/integrations/directus
- https://directus.io/guides/directus-plus-supabase/

## 📌 Requirements

- Docker ([Docker](https://docs.docker.com/engine/install/ubuntu/) +
  [Docker Compose](https://docs.docker.com/compose/install/))
- Git

#### Supported Databases
- PostgreSQL 10+

## ⚙️ Installation
1 - Get the code
```bash
git clone https://github.com/Youssef-Harby/supabase-directus-template.git
```
2 - Go to project directory
```bash
cd supabase-directus-template
```
3 - edit .env file to your configs
```bash
nano .env
```
hint: ctrl + x >> y >> enter to save the edits with nano

4 - up the `docker-compose.yml` file with Docker and Docker Compose (this command will pull all the images and run it)
```bash
docker compose up -d
```
hint: for older docker versions you may need to run with `docker-compose up -d`

- Enable PostGIS to use Geometry features on PostgreSQL and Directus Dashboard from Supabase Studio: http://localhost:3000/
- Directus: http://localhost:8055/
