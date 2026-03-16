# fw221-interdisciplinary-creative-project

## Topic

My project explores how cultural and media portrayals of nature and wildlife have impacted societal perceptions of conservation, environmental justice, and endangered species.

## Product

The "product" that I am creating in response to my topic for this project is a digital informational brochure in the form of a website. As a Computer Science major at NC State, I felt that this format would best demonstrate my creativity. In addition, I want to challenge myself by utilizing a tech stack that I haven't used often (C#.NET) for this project so that by creating this product, I will not only learn more about conservation, but also more about my own aspirational professional field of web development!

Due to the digital format of my project, you will notice that I have made the decision to open-source my code for the "product." I maintain that this decision is crucial for providing valuable insights into my creative process in an accessible way and will **not** result in any higher of a risk for enabling academic dishonesty compared to the analogous for other potential creative product formats. I will obviously not be open-sourcing my PackBack writing assignment submission alongside the code for my project.

## How to Run Project Locally
### Option 1: Visual Studio 
1. Open the project in Visual Studio from the solution file (`File` > `Open` > `Project/Solution` > `fw221-interdisciplinary-creative-project/BlazorApp/BlazorApp.sln`)
2. After opening the project/solution in Visual Studio, click on the green "Run" button. This will start up the project locally on `https://localhost:7119/`
   <img width="795" height="59" alt="image" src="https://github.com/user-attachments/assets/dc9f57e8-f45c-437b-ac20-ab3eb87b5a94" />
3. The last step will also automatically open a terminal window. To stop the local web server, press `Ctrl` + `C` in this terminal window. 

### Option 2: dotnet CLI
1. Make sure that you have .NET installed. If you already have Visual Studio installed, then you probably already have .NET installed through there. However, if you do **not** have Visual Studio or .NET installed, see [Microsoft's official documentation about how to install the .NET SDK](<https://learn.microsoft.com/en-us/dotnet/core/install/>).
2. Open a terminal window and navigate to the root directory of the Blazor app:
   ```
   $ cd fw221-interdisciplinary-creative-project\BlazorApp\BlazorApp
   ```
3. Run the following command to start up the local web server on `http://localhost:5255/`:
   ```
   $ dotnet run
   ```
