# AgileX

HTML and CSS product pages for AgileX Robotics mobile robot platforms, part of the Trossen Robotics web projects. These platforms serve as the base for industrial, research, and educational robotics applications, and most are ROS-compatible with open-source software support. Also includes the AgileX brand landing page.

## Products

| Product | Type | Description | Folder |
|---|---|---|---|
| Bunker Pro | Tracked | Off-road chassis rated IP67 with a 120 kg payload. | `Bunker Pro/` |
| Bunker Mini | Tracked | Compact modular chassis, 25 kg payload per current AgileX and Trossen listings. | `Bunker-Mini/` |
| Ranger Mini | Omnidirectional | Four-wheel independent steering with zero turning radius. Spin, traverse, diagonal, and Ackermann modes. | `Ranger-Mini/` |
| Hunter 2.0 | Front-wheel Ackermann | Built for autonomous driving and large payloads (150 kg). | `Hunter 2.0/` |
| Hunter SE | Front-wheel Ackermann | In-wheel hub motors, up to 4.8 m/s, quick-release battery. | `Hunter SE/` |
| LIMO | Multi-mode | Compact ROS robot for education and research, controllable from the LIMO app. Supports omnidirectional, tracked, Ackermann, and four-wheel differential steering. | `LIMO/` |
| LIMO Pro | Multi-mode | LIMO with more computing power, longer battery life, and ROS 2 support. | `LIMO Pro/` |
| Ranger Mini | Omnidirectional | Compact omnidirectional platform. | `Ranger-Mini/` |
| Scout 2.0 | 4-wheel differential | Industrial base platform for indoor and outdoor use, with top slide rails for sensors and modules. | `Scout 2.0/` |
| Scout Mini | 4-wheel differential | Compact platform, 10 kg payload at up to 10 km/h. Optional mecanum wheels for omnidirectional driving. | `Scout-Mini/` |
| Tracer | 2-wheel differential | Low-profile indoor logistics AGV. 100 kg payload, about 4 hours per charge. | `Tracer/` |

## Structure

- Each product folder holds that product's `.html` and `.css` files, plus its images
- `Landing Page/` - the AgileX brand landing page
- `AgileX-Universal-code.css` - shared styles used by multiple pages
- `Icons/` - shared icons used across product pages

## Usage

No install or build step. Open any product's `.html` file in a browser to preview it. Keep the folder structure intact, or shared styles and images may not load.

## Notes

- Each product has its own HTML and CSS, apart from the shared stylesheet listed above.
- Changes to `AgileX-Universal-code.css` can affect several pages, so check them after editing.