pm.test("Verify Latitude and Longitude", function () {
    const responseData = pm.response.json();
    pm.expect(responseData.coord.lat).to.equal(51.51);
    pm.expect(responseData.coord.lon).to.equal(-0.13);
});
