# Kirill Isakov

********** 
> ##### Contact information:
* [[GitHub](https://github.com/porneliusss) 
* [Vk](https://vk.com/llliixxx)
- Email: isakovkirill123@gmail.com
- Phone: +375333676908

# About me
I am a second-year computer science student. Live in Belarus.
My main area of interest is related to software development, I also want to develop in the direction of web-development and
to study both front-end and back-end. Although I haven't had any formal work experience or internships, I'm dedicated to gaining practical knowledge through engagement in various projects. My focus extends beyond acquiring specific technologies and tools; I strive to enhance my logical thinking and problem-solving abilities. Actively tackling diverse tasks allows me to develop strong analytical and solution-oriented skills.

## My stack of technologies 
 - C# 
 - JS
 - C++
 - SQL

## English Level
- B1

## Skills
- **Programming Languages:** C#, C++, SQL, JS
- **Frameworks:** Spring Boot, .NET Framework
- **Methodologies:** Object-Oriented Programming, Agile Software Development
- **Version Control Systems:** Git
- **Development Tools:** Visual Studio, IntelliJ IDEA, Unreal Engine Creation Platform, Unity Editor
- **Game Development:** UE5, Unity
- **3D Modeling:** Blender


## Code example
Working with API (C#)
```
using System;
using System.Net.Http;
using System.Threading.Tasks;

public class Program
{
    public static async Task Main(string[] args)
    {
        using (HttpClient client = new HttpClient())
        {
            string apiUrl = "https://api.example.com/data";
            
            HttpResponseMessage response = await client.GetAsync(apiUrl);
            
            if (response.IsSuccessStatusCode)
            {
                string content = await response.Content.ReadAsStringAsync();
                Console.WriteLine(content);
            }
            else
            {
                Console.WriteLine("Error while executing request");
            }
        }
    }
}
```

Working with files (C++)
```
#include <iostream>
#include <fstream>
#include <string>

int main() {
    std::string fileName = "example.txt";
    std::ofstream outFile(fileName);

    if (outFile.is_open()) {
        outFile << "Hello, world!" << std::endl;
        outFile.close();
        std::cout << "File written successfully" << std::endl;
    }
    else {
        std::cout << "Failed to open file" << std::endl;
    }

    return 0;
}
```