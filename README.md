## Next.js Dashboard App

Learning how to use Next.js App Router.

### Features

- CSS
- Fonts & Images
- Layouts & Pages
- Navigation
- Database
- Data Fetching
- Static & Dynamic Rendering
- Streaming
- Partial Prerendering
- Search & Pagination
- Data Mutations (CRUD)
- Error Handling
- Accessibility
- Authentication
- SEO Metadata

### user stories

- Users can view all invoices (dashboard)
- Users can create an invoice (dashboard/invoices/create)
- Users can edit an invoice (dashboard/invoices/:id/edit)
- Users can delete a invoice (dashboard/invoices/:id/delete)

#### resourceful routes:

| URL                           | HTTP Verb | Action | What it Does         |
| ----------------------------- | --------- | ------ | -------------------- |
| /dashboard                    | GET       | index  | See all invoices     |
| dashboard/invoices/create     | POST      | create | Create a new invoice |
| dashboard/invoices/:id/edit   | POST      | edit   | Edit an invoice      |
| dashboard/invoices/:id/delete | DELETE    | show   | Delete an invoice    |

#### Dev Notes

test username: user@example.com

test password: 123456
