<table>
    <tr>
        <th align="left" rowspan="2">
            <a href="#core-systems">Core Systems</a>
        </th>
        <td align="center">Localization</td>
        <td align="center">
            <a href="#low-level-rendering-engines">Low-level Rendering Engines</a>
        </td>
        <td align="center">Math</td>
    </tr>
    <tr>
        <td align="center">Memory Management</td>
        <td align="center"></td>
        <td align="center"></td>
    </tr>
    <tr>
        <th align="left">
            <a href="#platform-independence-layer">Platform Independence Layer</a>
        </th>
        <td align="center">File System</td>
        <td align="center">
            <a href="#graphics-device-hal">Graphics Device HAL</a>
        </td>
        <td align="center"></td>
    </tr>
    <tr>
        <th align="left">
            <a href="3rd-party-sdks">3rd Party SDKs</a>
        </th>
        <td align="center">
            <a href="#graphics-device-apis">Graphics Device APIs</a>
        </td>
        <td align="center">Physics Libraries</td>
        <td align="center"></td>
    </tr>
</table>

# Core Systems

## Low-level Rendering Engines

<table>
    <tr>
        <th>Crate</th>
        <th>Stats</th>
        <th>DX11</th>
        <th>DX12</th>
        <th>Metal</th>
        <th>OpenGL</th>
        <th>OpenGL ES</th>
        <th>Vulkan</th>
        <th>WebGL</th>
    </tr>
    <tr>
        <td>
            <a href="https://github.com/amethyst/rendy">rendy</a>
            </td>
        <td>
            <img src="https://img.shields.io/github/stars/amethyst/rendy" alt="GitHub Stars" />
            <br />
            <a href="https://crates.io/crates/rendy">
                <img src="https://img.shields.io/crates/v/rendy.svg" alt="Crates.io Version" />
            </a>
            <br />
            <img src="https://img.shields.io/badge/evaluated-v0.4.1-yellow" alt="Evaluated Version" />
            <br />
            <img src="https://img.shields.io/badge/maintenance-actively--developed-brightgreen" alt="Maintenance Status" />
        </td>
        <td align="center">✔</td>
        <td align="center">✔</td>
        <td align="center">✔</td>
        <td align="center">2.1+</td>
        <td align="center">2+</td>
        <td align="center">✔</td>
        <td align="center">✔</td>
    <tr>
</table>

# Platform Independence Layer

## Graphics Device HAL

<table>
    <tr>
        <th>Crate</th>
        <th>Stats</th>
        <th>DX11</th>
        <th>DX12</th>
        <th>Metal</th>
        <th>OpenGL</th>
        <th>OpenGL ES</th>
        <th>Vulkan</th>
        <th>WebGL</th>
    </tr>
    <tr>
        <td>
            <a href="https://github.com/gfx-rs/gfx">gfx</a>
            </td>
        <td>
            <img src="https://img.shields.io/github/stars/gfx-rs/gfx" alt="GitHub Stars" />
            <br />
            <a href="https://crates.io/crates/gfx-hal">
                <img src="https://img.shields.io/crates/v/gfx-hal.svg" alt="Crates.io Version" />
            </a>
            <br />
            <img src="https://img.shields.io/badge/evaluated-v0.3.1-yellow" alt="Evaluated Version" />
            <br />
            <img src="https://img.shields.io/badge/maintenance-actively--developed-brightgreen" alt="Maintenance Status" />
        </td>
        <td align="center">✔</td>
        <td align="center">✔</td>
        <td align="center">✔</td>
        <td align="center">2.1+</td>
        <td align="center">2+</td>
        <td align="center">✔</td>
        <td align="center">✔</td>
    <tr>
</table>

# 3rd Party SDKs

## Graphics Device APIs

<table>
    <tr>
        <th>Crate</th>
        <th>Stats</th>
        <th>bindgen</th>
        <th>DX11</th>
        <th>DX12</th>
        <th>Metal</th>
        <th>OpenGL</th>
        <th>OpenGL ES</th>
        <th>Vulkan</th>
        <th>WebGL</th>
    </tr>
    <tr>
        <td>
            <a href="https://github.com/MaikKlein/ash">ash</a>
            </td>
        <td>
            <img src="https://img.shields.io/github/stars/MaikKlein/ash" alt="GitHub Stars" />
            <br />
            <a href="https://crates.io/crates/ash">
                <img src="https://img.shields.io/crates/v/ash.svg" alt="Crates.io Version" />
            </a>
            <br />
            <img src="https://img.shields.io/badge/evaluated-v0.29.0-yellow" alt="Evaluated Version" />
            <br />
            <img src="https://img.shields.io/badge/maintenance-actively--developed-brightgreen" alt="Maintenance Status" />
        </td>
        <td align="center">✘</td>
        <td align="center">✘</td>
        <td align="center">✘</td>
        <td align="center">✘</td>
        <td align="center">✘</td>
        <td align="center">✘</td>
        <td align="center">✔</td>
        <td align="center">✘</td>
    <tr>
    <tr>
        <td>
            Example: <br />
            <a href="https://github.com/lucidscape/vulkan">vulkan</a>
            </td>
        <td>
            <img src="https://img.shields.io/github/stars/lucidscape/vulkan" alt="GitHub Stars" />
            <br />
            <a href="https://crates.io/crates/vulkan">
                <img src="https://img.shields.io/crates/v/vulkan.svg" alt="Crates.io Version" />
            </a>
            <br />
            <img src="https://img.shields.io/badge/evaluated-v0.0.1-yellow" alt="Evaluated Version" />
            <br />
            <img src="https://img.shields.io/badge/maintenance-deprecated-red" alt="Maintenance Status" />
        </td>
        <td align="center">✘</td>
        <td align="center">✘</td>
        <td align="center">✘</td>
        <td align="center">✘</td>
        <td align="center">✘</td>
        <td align="center">✘</td>
        <td align="center">✔</td>
        <td align="center">✘</td>
    <tr>
</table>
