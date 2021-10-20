# L-Jest
To run the testing you have to put the coman "npm run test"

If you want to run a folder in specifically you can put the coman "npm run test + name of the folder"

- toBeNull coincide solo con null
- toBeUndefined coincide solo con undefined
- toBeDefined es el opuesto a toBeUndefined
- toBeTruthy coincide con lo que sea que el condicional if devuelva como true
- toBeFalsy coincide con lo que sea que el condicional if devuelva como false
- .not.toBeTruthy

-----------------------------------------------------------

test('dos mas dos', ()=>{
    const value = 2+2;
    expect(value).toBeGreaterThan(3);
    expect(value).toBeGreaterThanOrEqual(3.5);
    expect(value).toBeLessThan(5);
    expect(value).toBeLessThanOrEqual(4.5);

    // toBe y toEqual son equivalentes para números
    expect(value).toBe(4);
    expect(value).toEqual(4);
})