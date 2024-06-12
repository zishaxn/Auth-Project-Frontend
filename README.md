# Frontend

This is the frontend of the project. The backend can be found [here](https://github.com/zishaxn/Auth-Project-Backend).

## Run Locally

### Navigate to the frontend directory & install dependencies

```bash
cd frontend
npm install
```

### Create a `.env` file at the root and add the `VITE_API_URL`. This is the URL of the backend API.

```bash
VITE_API_URL=http://localhost:4004
```

### Start the dev server

```bash
# runs on http://localhost:5173
npm run dev
```

## 🛠️ Build

To build the frontend, run the following command in the frontend directory:

```bash
npm run build
```

---

## Includes

- Register, login, logout, profile, account verification, password reset
- Send emails for account verification and password reset
- Get and remove sessions
- Frontend forms for login, register, reset password, etc.
- Custom React hooks to manage auth state & application data

![UI](https://github.com/nikitapryymak/mern-auth-jwt/raw/main/preview.jpg)


### Technologies Used

- **React**: For building the user interface
- **Chakra UI**: For styling the application
- **React Query**: For data fetching and state management

### Acknowledgement
Thanks To [Nikita](https://github.com/nikitapryymak) For This Amazing Tutorial.
