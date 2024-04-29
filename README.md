# NU Carpool

This is a web app for Northeastern University's students to assists them in finding groups for carpooling while on co-op.

Trigger
 

- Clone the project, add environment variables (listed below) in `.env`.
 
```env
# Prisma


DATABASE_URL=mysql://nucarpool_phrasetone:d170052e6469bb138be56820917e15f3546dc06d@kxx.h.filess.io:3307/nucarpool_phrasetone

# Next Auth

NEXTAUTH_SECRET==http://localhost:3000
NEXTAUTH_URL=# https://generate-secret.vercel.app/32

# Mapbox

NEXT_PUBLIC_MAPBOX_ACCESS_TOKEN=

# AWS
ACCESS_KEY_ID_AWS=
SECRET_ACCESS_KEY_AWS=
REGION_AWS=

#Azure Provider (Can be switched out for other Auth Providers)
AZURE_CLIENT_ID=
AZURE_CLIENT_SECRET=
AZURE_TENANT_ID=
```

Then do `yarn` and `yarn dev` to get the project running.

## Tech Stack

- Framework: NextJS + Typescript
- Component Library: TailwindCSS + Headless UI
- Authentication: NextAuth
- Map API: Mapbox
- Backend: Serverless with trpc + Prisma + mysql (hosted on PlanetScale)

This is also known as the T3 Stack. More details can be found [here](https://init.tips).
