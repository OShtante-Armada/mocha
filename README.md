# mocha chai

#simple structure

describe("FunctionName", function() {
it("What function does", function() {
assert.equal(actual result, expected result);
});
});

E.g.,
describe ("Math.sqrt", function(){
it("returns the square root", function(){
assert.equal(Math.sqrt(x), x\*x);
});
});

#Mocha framework provides common testing functions as:
#describe("...", function(){...}) - we describe the function Math.sqrt
#it("...", function(){...}) - block where we describe the particular use case.

#Chai library provides many assertions as assert.equal("", "")
