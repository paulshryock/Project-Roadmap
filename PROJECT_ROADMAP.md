# Project Roadmap

1. Business Goals
1. Strategy
1. Server Setup
1. Information Architecture
	1. Content Audit
	1. Content Inventory
	1. User Personas
	1. User Flows
	1. Site Map
	1. Wireframes
1. Development
1. Design
1. Quality Assurance
1. Testing & Debugging
1. Analytics & Reporting
1. Deployment

## Business Goals

## Strategy

## Information Architecture

### Content Audit (for existing projects)

If starting a brand new project, skip to Content Inventory.

If re-working an existing project, list all existing pages, posts, content, and media that the site currently holds. Include a title, page slug, and content type for each item.

#### Example

| Title | Slug | Type |
|-------|------|------|
| Contact Us | /contact | page |
| Blog | /news | archive |
| Aliquam tincidunt mauris eu risus | /news/category/aliquam-tincidunt-mauris-eu-risus | article |
| Vestibulum auctor | /video/vestibulum-auctor | video |
| Company Logo | /uploads/company.svg | image |

- Generate XML Sitemap
- Generate Screenshots
- Audit Tools
	- https://urlprofiler.com/
	- https://www.stillio.com/

### Content Inventory

List all pages, posts, content, and media that the site will hold. Include a title, page slug, content type, taxonomy, taxonomy term(s), author, and owner for each item. Optionally include publishing dates, and other data points. This is a more robust, updated, finalized version of the Content Audit.
 
#### Content Types

##### Examples

- Page
- Article
- Archive
- Video
- Image
- Product
- Event
- Testimonial
- Case Study
- Interview
- Client
- Form

#### Content Taxonomies

##### Examples

- Category
- Tag
- Tier
- Color

#### Content Models

List all data fields that will exist for each Content Type.

##### Example

- Content Status
	- Published (is live)
	- Scheduled (is approved, and will go live at a scheduled date)
	- Approved (is approved, but has not yet been scheduled or published)
	- Pending Approval (is written and ready for revisions or approval)
	- Draft (is being written or revised)
- Article
	- Title
	- Slug
	- Status
	- Publish Date
	- Author (What individual will be displayed as the author of this content?)
	- Owner (What team or role owns governance of this content?)
	- Summary Excerpt
	- Featured Image
	- Content (Main body of the article)
	- Taxonomy

#### Content Inventory Example

| ID | Title | Slug | Type | Taxonomy | Term(s) | Author | Owner |
|-------|-------|------|------|----------|---|---|---|
| 1 | Product 1 | /product-1 | product | Tier | Enterprise | Erica Romaguera | Marketing |
| 2 | Lorem Ipsum | /lorem-ipsum | article | Category | Technology | Caleigh Jerde | InfoSec |

### User Personas

Set realistic examples of target audience members. List the user’s name, occupation, education, demographic characteristics, computer/web experience, and site goals or likely tasks.

#### Examples:

##### Internal

- Clients: Existing clients who have already hired us
	- Schedule a Consultation
	- Get an Estimate
	- Start a Project
- Leads: People who are considering becoming clients, or shopping around
	- Browse (see our work, learn about our team and expertise)
	- Decide if we’re the right service provider
	- Schedule a Consultation
	- Get an Estimate
	- Start a Project
	- Download Freebies and Resources
	- Share with colleagues and managers
- Colleagues: People whose role wouldn’t make sense to hire us
	- Browse (see our work, learn about our team and expertise)
	- Download Freebies and Resources
	- Share with colleagues and managers
- Executives: People who are business leaders at Realogy
	- Browse (see our work, learn about our team and expertise)
	- Share with brand and business unit leaders and managers

##### External

- Vendors: External companies (printers, etc.) who deliver services to us
	- Find email, phone number, and physical address
	- Download print files
	- Send us an invoice
- Freelancers: External people (designers, photographers, etc.) working for us, either on-site or remotely
	- Find email, phone number, and physical address
	- Browse (see our work, learn about our team and expertise)
	- Download Creative Briefs
	- Send us an invoice
- Job Seekers: External people who are interested in working at Realogy 
	- Browse (see our work, learn about our team and expertise)
	- Send us a cover letter, resume, and portfolio

### User Flows

Illustrates a sequence of events that a user might go through in order to accomplish their goal(s).

### Site Map

Documents the various pages or page types throughout the site and the user paths to and from them. (Looks like a flow chart.)

### Wireframes

Shows the items on the page, the importance of each item on the page, and the behavior of each item on page. This is not about design/layout choices.

## Development

## Design

## Quality Assurance

## Testing & Debugging

## Analytics & Reporting

## Deployment