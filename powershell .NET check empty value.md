## powershell .NET check empty value
You can use the .NET class System.String to check if a string variable is null or empty in PowerShell. The IsNullOrEmpty() method indicates whether the specified string is empty or null. [It returns True if the string is empty and False if it is not empty](https://itsmycode.com/check-if-a-string-is-null-or-empty-in-powershell/)
Here’s an example of how you can use it:
```
if ([string]::IsNullOrEmpty($variable)) {
    Write-Host "Variable is null or empty"
}

```
This code checks if the variable is null or empty. If it is, it will output “Variable is null or empty” to the console

#### Learn more:
1. [itsmycode.com](https://itsmycode.com/check-if-a-string-is-null-or-empty-in-powershell/)
2. [shellgeek.com](https://shellgeek.com/powershell-isnullorempty-check-if-variable-is-null/)
3. [tutorialspoint.com](https://www.tutorialspoint.com/how-to-check-if-the-file-is-empty-using-powershell)
4. [stackoverflow.com](https://stackoverflow.com/questions/13738634/how-can-i-check-if-a-string-is-null-or-empty-in-powershell)
5. [thinkpowershell.com](https://thinkpowershell.com/test-powershell-variable-for-null-empty-string-and-white-space/)
6. [stackoverflow.com](https://stackoverflow.com/questions/31081186/how-to-check-empty-null-csv-value)

