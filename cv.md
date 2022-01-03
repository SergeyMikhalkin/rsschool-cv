# __Sergey Mikhalkin__

## Contacts
   - Location: Navapolatsk, Belarus
   - Phone: +375 29 710 02 67
   - Email: Sergey.Mikhalkin.dev@gmail.com
   - GitHub account: [sergeymikhalkin] https://github.com/SergeyMikhalkin
   - LinkedIn account: [sergey-mikhalkin](https://linkedin.com/in/sergey-mikhalkin)

## About
    My dream is to become a software engineer. Strongly believe that programming languages are the tools for achieving working goals. 

## Skills
    - HTML
    - CSS
    - C#
    - SQL
    - Xamarin

## Code example
        ```
        // расчет вязкости при смешивании 2х компонентов
        // viscosity1, viscosity2 - вязкость 
        // quantity1, quantity2 - количество
        public static bool CalcViscosity(double viscosity1, double quantity1, double viscosity2, double quantity2, out double result)
        {
            result = 0;

            try
            {
                double a = quantity1 * Math.Log10(Math.Log10(viscosity1 + 0.8d));
                double b = quantity2 * Math.Log10(Math.Log10(viscosity2 + 0.8d));

                double c = Math.Pow(10.0d, (a + b) / (quantity1 + quantity2));
                c = Math.Pow(10.0d, c);
                c -= 0.8d;

                result = c;
            }
            catch (Exception)
            {
                return false;
            }

            return true;
        }
        ```
## Experience
    Since 2016 work as a Software developer at oil refinery 

## Education
    ### Polotsk State University (Computers, Systems and Networks)
    ### Epam (ASP.NET)
    ### Andersen (Web development)
    ### RS School (Front-end)

## Languages
 - Russian (native)
 - English (B1)

