# Open Source Gas Mask

![Image of gas mask](/images/gasmask.png)

NOTE: This is a preliminary design, that still needs testing and refinement.  Do not rely on this to save your life just yet.

## About

This is an open source 3D printable gas mask design. It consists of 3 main components - the mask itself, the filter canister, and the exhale valve. Each component in turn consists of multiple parts. The documents contained in this repository will guide you through selecting and building each component you need.

## Components

### Mask

Masks are either full face or half face, depending on whether they protect the mouth/nose and eyes or just the mouth and nose. Half face masks are simpler, cheaper, and faster to make in the event that eye protection is not necessary or is accomplished with separate equipment.

All masks in this repository use 40mm NATO threads to connect to other components when necessary. This also means that commercially available 40mm NATO threaded filter canisters are directly compatible with these masks. Commercial filter canisters with different connector standards may be used with the masks in this repository by using an adapter from the `adapters` folder.

See the `masks` folder readme for a comparison of mask designs.

### Filter

If filters are commercially available, they are always preferable to homemade filters. However, in the event that filter supply is expensive or unavailable, the included designs allow for homemade filters. All masks in this repository use standard 40mm NATO threaded filter canisters, which are located in `filters/NATO_40mm`.

If an adapter is in use to convert NATO threads to a different standard, you may want to build the appropriate filter canister found in the appropriate subfolder in `filters`. This is especially useful if you wish to easily switch between commercially available filters and homemade filters without having to remove the adapter.

The filter material is activated charcoal - you can buy this at any pet store. Put a layer of cotton batting in the bottom of the canister, then fill with activated charcoal, then put another layer of cotton on top, and connect the canister into the mask. See the documentation included with the specific filter design for more detailed instructions.

### Valve

The use of an exhale valve reduces the chance of asphyxiation due to re-breathing the same air, as well as prolonging the life of the filter media and mitigating visor fogging on full face masks. All masks in this repository should contain provisions for an exhale valve. For your safety, ensure every assembled mask has an exhale valve installed and operating properly. The mask documentation should include guidance on installing the exhale valve.

See the `valves` folder readme for an overview of valves.

### Adapters

To ensure compatibility between components in this repository, all connections use standard 40mm NATO threads. As a result, adapters are required to use filter canisters of a different connector standard. The `adapters` folder contains a catalog of 3D printable adapters for converting the NATO threads of the mask to many other standards.

* When using an alternate connector type, ensure that a seal is properly made and any required gaskets or additional materials are in place.
* It may make assembly and use of the mask easier if the adapter is permanently glued to the mask. This is a good option if support for multiple connector standards is not needed.

## Safety Warnings
***This mask is still in development. You should not use this in a real world situation until the mask is done, and any testing you do should be in a controlled environment with someone else present !!!***

1. Print Material: PLA can be brittle and sharp in the event that it breaks. It is recommended to use PETG or Nylon if possible, especially if the risks of PLA shattering could be an issue in the environment you plan on using it or if you expect the mask to be subjected to stresses or impacts.
2. Face Gasket: When using a hard plastic material, it is extremely unlikely that a proper seal will form between the mask and the user's face. Some form of gasket or appropriate foam should be added around the edge of the mask to ensure an airtight seal.
3. Fit / Seal / Leak Testing: It is highly recommended to test the mask for leaks and fit quality.
4. Exhale / Vent Valve: The amount of dead space inside the mask and filters can lead to a risk of asphyxiation. All masks in this repository have provisions for installing an exhale valve. Please be sure to assemble and install one in every mask. Currently, there are no completed valve designs for the masks in this repository. Designs in this repository should not be used in real world scenarios until valves are available.
5. Gaskets / Glue: Every connection point between parts must have an airtight seal with the exception of filter canister lids on the dirty side of the filter media. See the documentation included with each part to ensure the proper seal is achieved. Alternatively, parts that do not need to be disassembled may be glued together with the appropriate glue.

## Contributing

Pull requests welcome!
