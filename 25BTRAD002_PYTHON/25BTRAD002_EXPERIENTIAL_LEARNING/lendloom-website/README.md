[README_Enhanced.md](https://github.com/user-attachments/files/35010390/README_Enhanced.md)
::: {align="center"}
# ✨ LENDLOOM

### 🎓 Campus Exchange --- Buy · Sell · Swap · Rent

```{=html}
<p>
```
`<strong>`{=html}A student-focused marketplace built to make campus
exchanges simpler, safer, and more connected.`</strong>`{=html}
```{=html}
</p>
```
```{=html}
<p>
```
`<img src="https://img.shields.io/badge/STATUS-IN%20DEVELOPMENT-7C3AED?style=for-the-badge&logo=github" alt="Status: In development">`{=html}
`<img src="https://img.shields.io/badge/BUILT%20WITH-BUN-FBF0DF?style=for-the-badge&logo=bun&logoColor=000000" alt="Built with Bun">`{=html}
`<img src="https://img.shields.io/badge/FRONTEND-VITE-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite">`{=html}
`<img src="https://img.shields.io/badge/DATABASE-SUPABASE-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase">`{=html}
```{=html}
</p>
```
```{=html}
<p>
```
`<em>`{=html}One campus. Many possibilities. Less waste, more value.
💜`</em>`{=html}
```{=html}
</p>
```
:::

------------------------------------------------------------------------

## 🌈 What is Lendloom?

**Lendloom** is a campus marketplace project designed around the
everyday needs of students. It brings multiple ways to exchange items
into one place---whether you want to **sell something, find a rental,
swap an item, or make an exchange request**.

The project source includes the marketplace interface, styling assets,
automated tests, and database migration history.

------------------------------------------------------------------------

## 🚀 Explore the Marketplace

  -----------------------------------------------------------------------
  🛍️ Feature                          💡 What it offers
  ----------------------------------- -----------------------------------
  **Buy & Sell**                      Marketplace screens for
                                      student-to-student sales.

  **Rentals**                         A place to explore rental listings.

  **Swaps**                           Screens for exchanging items with
                                      other students.

  **Exchange Requests**               Marketplace flows for requesting an
                                      exchange.

  **Student Profiles**                Profile screens as part of the
                                      campus experience.
  -----------------------------------------------------------------------

------------------------------------------------------------------------

## 🧩 What's Inside?

-   🎨 **Interface & styling** --- marketplace screens, styling, and
    icons.
-   🖼️ **Visual assets** --- includes the campus exchange photograph.
-   🗃️ **Database migrations** --- SQL migration history for marketplace
    records and access protections.
-   🧪 **Automated tests** --- test suite included in the project.
-   ⚡ **Development setup** --- Vite / TanStack project configuration.

------------------------------------------------------------------------

## 🛠️ Tech & Tools

::: {align="center"}
  Tool                Role
  ------------------- -----------------------------------------------
  **Bun**             Package installation, scripts, and tests
  **Vite**            Development server / build tooling
  **TanStack**        Project configuration
  **Lovable Cloud**   Required cloud project and marketplace schema
  **Supabase**        Browser environment configuration
:::

------------------------------------------------------------------------

## ⚙️ Run Lendloom Locally

### 1. Prerequisites

Before you begin, make sure you have:

-   [Bun](https://bun.sh/) installed.
-   Your own **Lovable Cloud** project.
-   The matching marketplace schema and storage bucket configured.

### 2. Get the project ready

``` bash
bun install
```

### 3. Configure environment variables

Create a local `.env` file using `.env.example` as your template. Add
the **public project URL** and **publishable key** from your own Lovable
Cloud setup.

The browser app expects:

``` env
VITE_SUPABASE_URL=your_public_project_url
VITE_SUPABASE_PUBLISHABLE_KEY=your_publishable_key
```

> 🔐 **Security first:** Never place a service-role key or any other
> private credential in browser-exposed environment variables.

### 4. Start the development server

``` bash
bun run dev
```

### 5. Run the tests

``` bash
bun test
```

------------------------------------------------------------------------

## 🗄️ Database & Data Notes

The migration files are included as **source/reference material**. They
do not automatically create or connect a database.

This download does **not** include or transfer:

-   Student accounts
-   Marketplace listings
-   Exchange requests
-   Uploaded photos
-   Passwords or login sessions

Existing data must be exported and imported separately. To run the app
with backend functionality, configure your own cloud project with the
matching schema and storage bucket.

------------------------------------------------------------------------

## 🔒 Privacy & Security

This project download intentionally excludes:

-   🔑 Private environment files
-   🎟️ Access tokens
-   🕰️ Repository history
-   📦 Installed dependencies
-   🏗️ Generated build output

Keep credentials private, use your own environment configuration, and
never commit secrets to the repository.

------------------------------------------------------------------------

## 💜 The Lendloom Idea

A campus is full of useful things that are only needed for a short
time---or are ready for a new owner. Lendloom aims to make those
exchanges easier by bringing **sales, rentals, swaps, and requests**
together in a student-focused marketplace.

::: {align="center"}
### ♻️ Give things another life. Find what you need. Keep it on campus.

**Made for campus. Powered by community. ✨**
:::
