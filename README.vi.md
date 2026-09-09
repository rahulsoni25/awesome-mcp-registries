<div align="center">

# Awesome MCP Registries [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

**Danh sách tuyển chọn mọi nơi để xuất bản, niêm yết và nộp một [MCP (Model Context Protocol)](https://modelcontextprotocol.io) server** — registry chính thức, các directory tự động lập chỉ mục, registry nộp thủ công, awesome list và gallery của client — **kèm cách nộp vào từng nơi**.

[![License: CC0-1.0](https://img.shields.io/badge/license-CC0--1.0-lightgrey.svg)](./LICENSE)

🌐 **[English](./README.md)** · **[🇻🇳 Tiếng Việt](./README.vi.md)**

</div>

---

> **Vì sao có danh sách này?** Bạn xây xong một MCP server và lập tức gặp câu hỏi tiếp theo: **"niêm yết nó ở đâu để mọi người — và các AI client — tìm thấy?"** Câu trả lời nằm rải rác trong các bài blog và vài dòng tweet nửa nhớ nửa quên. List này gom các điểm đến về một chỗ, sắp theo loại, và nói rõ **mỗi nơi muốn nhận submission kiểu gì** để bạn cứ thế đi từ trên xuống. Mọi liên kết đều là điểm đến có thật, còn sống.

## Mục lục

- [Bắt đầu ở đây — Registry chính thức](#bắt-đầu-ở-đây--registry-chính-thức)
- [Directory tự động lập chỉ mục (nhận listing của bạn)](#directory-tự-động-lập-chỉ-mục-nhận-listing-của-bạn)
- [Directory & Registry nộp thủ công](#directory--registry-nộp-thủ-công)
- [Awesome List (mở pull request)](#awesome-list-mở-pull-request)
- [Gallery & Marketplace của Client](#gallery--marketplace-của-client)
- [Trước khi nộp — Checklist](#trước-khi-nộp--checklist)
- [Các Awesome List liên quan](#các-awesome-list-liên-quan)
- [Đóng góp](#đóng-góp)

## Bắt đầu ở đây — Registry chính thức

Làm cái này trước: phần lớn các directory khác đều nằm sau registry chính thức và mirror hoặc trỏ ngược về nó.

- [modelcontextprotocol/registry](https://github.com/modelcontextprotocol/registry) — MCP Registry **chính thức**, chuẩn tắc. Bạn xuất bản bằng CLI `mcp-publisher` (`mcp-publisher login` rồi `mcp-publisher publish`) với manifest `server.json` mô tả server, packages và remotes.
- [registry.modelcontextprotocol.io](https://registry.modelcontextprotocol.io) — API registry trực tiếp phục vụ các entry đã xuất bản (duyệt/tiêu thụ bằng lập trình).
- [Tài liệu MCP Registry](https://modelcontextprotocol.io/registry) — Tài liệu chính thức về registry, `server.json` và luồng xuất bản.
- [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers) — Repo các server tham khảo; mở PR ở đây là con đường cho server tham khảo / cộng đồng đáng chú ý.

## Directory tự động lập chỉ mục (nhận listing của bạn)

Các nơi này tự crawl GitHub công khai và các endpoint hosted — bạn chủ yếu cần làm cho repo dễ tìm thấy rồi **nhận quyền sở hữu (claim)** listing.

- [Glama](https://glama.ai/mcp/servers) — Registry + inspector lớn, tự lập chỉ mục server mã nguồn mở từ GitHub, trích xuất mọi tool/schema/annotation và chấm điểm chất lượng. Claim server để quản lý listing và badge.
- [PulseMCP](https://www.pulsemcp.com/) — Directory được bảo trì tích cực, cập nhật nhanh, hỗ trợ mạnh server remote HTTP. Nộp tại [pulsemcp.com/submit](https://www.pulsemcp.com/submit).
- [mcp.so](https://mcp.so/) — Một trong những directory MCP lớn nhất, lượng truy cập cao. Nộp qua form web tại [mcp.so/submit](https://mcp.so/submit).

## Directory & Registry nộp thủ công

Các nơi này cần một submission rõ ràng — form web, publish qua CLI, hoặc luồng kết nối GitHub.

- [Smithery](https://smithery.ai/) — Registry phổ biến được nhiều dev dùng; publish bằng CLI `smithery` hoặc kết nối repo GitHub (khai báo transport, ví dụ `http`).
- [Cursor Directory](https://cursor.directory/mcp) — Directory MCP cho cộng đồng đông đảo của editor Cursor; nộp qua form web.
- [mcpservers.org](https://mcpservers.org/) — Directory cộng đồng gọn nhẹ; nộp nhanh qua web / GitHub.
- [Fleur](https://www.fleurmcp.com/) — Marketplace kiểu app-store cho MCP; nộp server để được niêm yết.
- [mcp.run](https://mcp.run/) — Registry/runtime hosted cho các "servlet" MCP; publish để server cài đặt được.

## Awesome List (mở pull request)

Các awesome list trên GitHub hoạt động theo PR và cho backlink mạnh. Đọc `CONTRIBUTING` của từng list trước — vài list yêu cầu định dạng một dòng cụ thể (và một số catalog server yêu cầu badge/emoji cho mỗi mục).

- [punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) — Awesome list lớn nhất, chuẩn tắc về MCP server. Mục server cần link `owner/repo`, một badge điểm Glama và một emoji ngôn ngữ; mở PR từ fork đúng của *mạng này*.
- [wong2/awesome-mcp-servers](https://github.com/wong2/awesome-mcp-servers) — Một awesome list được tham chiếu rộng rãi khác (mạng GitHub riêng, khác list trên).
- [appcypher/awesome-mcp-servers](https://github.com/appcypher/awesome-mcp-servers) — Một list sớm và lớn (đã lưu trữ / chỉ đọc — tham khảo lịch sử).
- [AIAnytime/Awesome-MCP-Server](https://github.com/AIAnytime/Awesome-MCP-Server) — Catalog được bảo trì tích cực, có các mục phân loại (ví dụ commerce, travel & logistics).
- [TensorBlock/awesome-mcp-servers](https://github.com/TensorBlock/awesome-mcp-servers) — Awesome list rất lớn, phân loại, nhận PR server.
- [MobinX/awesome-mcp-list](https://github.com/MobinX/awesome-mcp-list) — Một list MCP server cô đọng, được tuyển chọn.

## Gallery & Marketplace của Client

Một số *client* MCP có gallery/extension store tích hợp sẵn — được niêm yết ở đó giúp server của bạn tiếp cận người dùng của client đó.

- [VS Code MCP](https://code.visualstudio.com/mcp) — Hỗ trợ MCP của Visual Studio Code và gallery server được tuyển chọn.
- [Cursor Directory](https://cursor.directory/mcp) — Đồng thời là gallery MCP trong ngữ cảnh của editor Cursor.

## Trước khi nộp — Checklist

Chuẩn bị sẵn những thứ này để mọi form hay PR đều trôi chảy:

- [ ] Một **repo GitHub công khai** với README rõ ràng (song ngữ là điểm cộng).
- [ ] Một manifest [`server.json`](https://modelcontextprotocol.io/registry) mô tả server, packages và/hoặc remotes.
- [ ] Một **endpoint còn sống** (với server remote, một URL Streamable HTTP phản hồi được) hoặc một package cài được.
- [ ] Một **mô tả một dòng**, một category, và vài tag.
- [ ] Một logo vuông (≥ 512×512 PNG) cho các directory có hiển thị logo.
- [ ] **Kiểm tra server trước** bằng một smoke test conformance để không nộp nhầm endpoint hỏng — ví dụ [mcp-conformance](https://github.com/tuanone123/mcp-conformance) (`npx mcp-conformance <url>`) hoặc [MCP Inspector](https://github.com/modelcontextprotocol/inspector) chính thức.
- [ ] Tùy chọn: một [`llms.txt`](https://llmstxt.org/) cho các crawler AI.

## Các Awesome List liên quan

- [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) — List chuẩn tắc về chính các MCP server.
- [awesome-mcp-testing](https://github.com/tuanone123/awesome-mcp-testing) — Công cụ test, đánh giá và xác thực MCP server trước khi ship.
- [awesome-mcp-devtools](https://github.com/punkpeye/awesome-mcp-devtools) — Dev tool, SDK và thư viện để xây MCP server.
- [Model Context Protocol](https://modelcontextprotocol.io) — Trang và tài liệu chính thức của giao thức.

## Đóng góp

Hoan nghênh đóng góp — xem [CONTRIBUTING.md](./CONTRIBUTING.md). Tóm tắt: **điểm đến phải có thật và link phải sống (HTTP 200)**, phải thật sự là nơi để xuất bản/niêm yết/nộp một MCP server, mỗi PR một mục đúng nhóm, kèm một dòng ghi chú đúng sự thật về *cách nộp*. Thêm vào cả `README.md` lẫn `README.vi.md`.

## Giấy phép

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](./LICENSE) — phát hành theo [CC0 1.0 Universal](./LICENSE). Trong phạm vi luật cho phép, các đóng góp viên từ bỏ mọi quyền tác giả với danh sách này. Mỗi điểm đến được liệt kê giữ **giấy phép riêng** — luôn kiểm tra nguồn trước khi dùng.
