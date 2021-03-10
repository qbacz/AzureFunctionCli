func init LocalFunctionProj --dotnet
cd LocalFunctionProj
func new --name HttpExample --template "HTTP trigger" --authlevel "anonymous"

http://localhost:7071/api/HttpExample?name=HelloWorld