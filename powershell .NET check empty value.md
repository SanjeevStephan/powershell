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
