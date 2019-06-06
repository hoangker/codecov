/**
 * Test we can create the Contact component
 */
import React from "react";
import { create } from "react-test-renderer";
import Coverage from "./Coverage";
describe("Coverage component", () => {
  test("it matches the snapshot", () => {
    const component = create(<Coverage/>); 
    expect(component.toJSON()).toMatchSnapshot();
  });
});
