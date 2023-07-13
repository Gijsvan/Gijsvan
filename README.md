print("Enter a number:")
local num = tonumber(io.read())

local result = 1
for i = 1, num do
    result = result * i
end

print(num .. "! = " .. result)
