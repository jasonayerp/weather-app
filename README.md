# .NET, .NET Blazor, and .NET MAUI Blazor Learners Weather App
This is a learner app designed to illustrate a minimally implemented "weather app" using various design practices including but not limited to: dependency-injection/dependency-inversion principle, domain driven design, unit of work, unit tests, service-repository pattern, abstraction, and more.
## About this app
This code and application is not meant to be used in any sort of production setting as it is only meant to help an up and coming dev who wants to explore the world of .NET and get up to speed on what an enterprise grade weather app could look like. This is only my opinion on how I would go about making the basis of such an app and as such does not promote any one practice, standard, or method of implementation.

You can use this app in conjunction with other learning material such as the official Microsoft docs.
## Projects and Applications
The follow projects and applications are included in this repository:
- Weather.Api: The backend application that serves weather data to client applications
- Weather.Web: The web client application that displays the weather data
- Weather.Desktop: The desktop client application that displays the weather data
- Weather.Core: A C# class library that contains core shared business logic agnostic classes, functions, services, and other logic
- Weather.Domains: A C# class library that contains busines logic models, validators, and other logic
- Weather.UI: A Razor class library that contains shared razor components
## Licensing - MIT License
Copyright (c) 2023 Jason Ayer

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.