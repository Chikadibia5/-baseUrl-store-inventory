# -baseUrl-store-inventory
pm.test("Status code is 200", function () {     pm.response.to.have.status(200); });  pm.test("Status code should have an OK", function () {     pm.response.to.have.status("OK"); }); var jasonData = pm.response.json() console.log(jasonData.pending) pm.test("confirm that pending inventory is 11")
