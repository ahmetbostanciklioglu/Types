# Types
Swift Types

**//To write a multiline string use """ triple quotes, and then write text inside triple quotes starting from next line** 

var stringFirst = """
First line 
second line 
third line
"""

**//When we write  stringFirst  inside print. Will see the multiline text**

print(stringFirst). 

**//To add some integer, float, bool, string or something else inside string you can use  string interpolation. To apply string interpolation write \(anyObjectYouCanWrite)**

var stringInterpolation = "This is a \(int)"
var stringInterpolation2 = "This is a \(stringFirst)"
var stringInterpolation3 = "This is a \(bool)"

**//MARK: - Constants string**

let constant = "this is a constant String object."

**//To show type annotations in string write String or [String] after constant or variable name or array name such as var exampleAnotation: String**


let typeSafetyConstantString : String = "String"
let typeSafetyConstantArray : [String] = ["1", "12", "23", "34", "45"]
