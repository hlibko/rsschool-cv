# Gleb Kochubey

**Contact Information:**  
- **Phone:** +1-123-456-7890  
- **Email:** hlibko@protonmail.com   
- **GitHub:** [github.com/hlibko](https://github.com/hlibko)  

---

## About Me

Motivated and dedicated software developer with a strong foundation in web development and modern programming practices. Committed to continuous learning and improvement, with a keen interest in creating clean, efficient, and scalable solutions.

---

## Skills

- **Programming Languages:** C#, JavaScript, SQL
- **Frameworks & Libraries:** .Net, Angular, Node.js
- **Development Tools:** Docker, Webpack
- **Methodologies:** Agile, Test-Driven Development (TDD), Continuous Integration (CI/CD)
- **Database Technologies:** MS SQL, PostgreSQL
- **Version Control:** Git, GitHub,

---

## Code Samples
```
public class Program
    {
        public static void Main(string[] args)
        {
            var myList = new List<int> { 1, 3, 5, 7, 9 };
            Console.WriteLine(BinarySearch(myList, 3)); // => 1
            Console.WriteLine(BinarySearch(myList, -1)); // => null gets printed as an empty string
        }

        private static int? BinarySearch(IList<int> list, int item)
        {
            var low = 0;
            var high = list.Count() - 1;

            while (low <= high)
            {
                var mid = (low + high) / 2;
                var guess = list[mid];
                if (guess == item) return mid;
                if (guess > item)
                {
                    high = mid - 1;
                }
                else
                {
                    low = mid + 1;
                }
            }

            return null;
        }
    }
```

---

## Work Experience

### Full-stack .NET Developer
**[Super.Voyage](https://www.super.voyage/)** — Stockholm  
[01/2026 – Present]  
Building and scaling a travel platform using Umbraco CMS (.NET) as a headless backend and React on the frontend. Responsible for designing content architecture, multilingual and SEO-friendly solutions, and cloud infrastructure on Microsoft Azure.

Key focus areas:
- Headless Umbraco CMS, content modeling, i18n & SEO
- React frontend with Astro (SSG/SSR)
- Azure App Service, Azure SQL, Blob Storage, CDN
- Azure DevOps (CI/CD pipelines, Git)
- Docker & containerized environments
- AI-driven features (SEO automation, content generation, recommendations)

---

## Projects

- **ASP.NET Core eCommerce App:** [SportsSln](https://github.com/hlibko/SportsSln)  
  This project showcases the development of a fully functional e-commerce application using ASP.NET Core. It demonstrates core ASP.NET features such as controllers, action methods, views, Razor Pages, Blazor components, routing, form validation, and authentication.

- **Note365:** [note365-web](https://github.com/hlibko/note365-web)  
  Note365 Web is a web application designed for efficient note-taking and organization. It allows users to create, edit, and categorize notes, set reminders, and access notes from any device with internet access. Built with a user-friendly interface, Note365 Web provides a seamless experience for personal and professional organization, featuring secure login, search functionality, and customizable settings to suit individual user needs.

---