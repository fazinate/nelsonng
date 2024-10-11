---
layout: ../layouts/BlogPost.astro
title: State of AI Report 2024
slug: state-of-ai-report-2024
description: How would AI become in 2024 and next?
tags:
  - technical
added: 2024-10-11T06:06:09.828Z
---

CÁC XU HƯỚNG AI TRONG NĂM 2024
(State of AI Report 2024)
🥇 Sự thống trị của OpenAI trong nghiên cứu AI đã bị thách thức, với các phòng thí nghiệm tiên tiến khác bắt kịp về hiệu suất. Claude 3.5 Sonnet, Gemini 1.5 và Grok 2 đều đã thu hẹp khoảng cách hiệu suất với GPT-4 khi hiệu suất mô hình hội tụ.
💡 OpenAI đã cải thiện đáng kể khả năng lập luận của LLM bằng cách chuyển đổi tài nguyên tính toán từ giai đoạn tiền huấn luyện và hậu huấn luyện sang giai đoạn suy luận. Kỹ thuật này, được gọi là "chain-of-thought", sử dụng học tăng cường để mở khóa khả năng giải quyết các bài toán toán học, khoa học và lập trình nhiều lớp mà LLM trước đây gặp khó khăn.
🔓 Các mô hình nguồn mở đã thu hẹp khoảng cách với các mô hình độc quyền tiên tiến. Llama 3 của Meta, được phát hành theo ba phiên bản từ tháng 4 đến tháng 9 năm 2024, có khả năng cạnh tranh với GPT-4 và Claude 3.5 Sonnet trong các tác vụ lập luận, toán học, đa ngôn ngữ và ngữ cảnh dài.
⚠️ Mối lo ngại đã được đặt ra về "ô nhiễm tập dữ liệu", trong đó dữ liệu kiểm tra hoặc xác thực bị rò rỉ vào tập huấn luyện. Các nhà nghiên cứu đã phát hiện ra sự sụt giảm hiệu suất đáng kể trong một số trường hợp khi các mô hình được kiểm tra trên một tập dữ liệu mới phản ánh phong cách và độ phức tạp của các điểm chuẩn đã được thiết lập.
🛠️ Các nhà nghiên cứu đang nỗ lực khắc phục các vấn đề trong các điểm chuẩn được sử dụng rộng rãi. Ví dụ, OpenAI đã cảnh báo rằng SWE-bench, công cụ đánh giá khả năng giải quyết các vấn đề phần mềm trong thế giới thực của mô hình, đã đánh giá thấp khả năng kỹ thuật phần mềm tự động của các mô hình.
🤔 Có những lo ngại rằng phương pháp đánh giá bằng "vibe" (cảm nhận) của cộng đồng về model ưa thích đang tạo ra những kết quả không chính xác. Bảng xếp hạng LMYS Chatbot Arena cho phép người dùng tương tác với hai chatbot được chọn ngẫu nhiên và cung cấp một đánh giá từ cộng đồng. Tuy nhiên, điều gây tranh cãi là điều này đã dẫn đến việc GPT-4 và GPT-4 Mini nhận được cùng một điểm số, thậm chí GPT-4 Mini còn vượt cả Claude Sonnet 3.5.
🧠 Các hệ thống neuro-symbolic (thần kinh-biểu tượng) đang trở lại, giúp khắc phục các yếu kém về khả năng lập luận và dữ liệu huấn luyện, 2 yếu tố thường khiến các hệ thống AI gặp khó khăn trong các bài toán và hình học. Một nhóm Google DeepMind/NYU đã tạo ra AlphaGeometry, một công cụ suy diễn biểu tượng đến xử lý vấn đề này.
✂️ Có thể thu nhỏ các mô hình mà không làm giảm hiệu suất. Nghiên cứu cho thấy các mô hình hoạt động tốt khi bị khéo léo lược bỏ các lớp (mạng thần kinh) sâu hơn. Các lớp này được thiết kế để xử lý thông tin phức tạp, trừu tượng hoặc cụ thể cho tác vụ.
🧪 Các mô hình chưng cất đang trở nên phổ biến hơn. Các làm là dùng các mô hình lớn để tinh chỉnh và tổng hợp dữ liệu huấn luyện để giúp huấn luyện các mô hình nhỏ. Google đã áp dụng phương pháp này, chưng cất Gemini 1.5 Flash từ Gemini 1.5 Pro, trong khi Gemma 2.9B được chưng cất từ Gemma 2.27B, và Gemma 2B từ một mô hình lớn hơn chưa được phát hành.
📱 Các mô hình được xây dựng cho thiết bị di động hiện đang cạnh tranh với các mô hình lớn hơn. Các công ty công nghệ lớn đang tìm cách triển khai AI ở quy mô lớn cho người dùng cuối. Họ sử dụng các mô hình LLM và multimodal có hiệu suất cao nhưng nhỏ có thể chạy trên điện thoại thông minh.
🤏 Việc lượng tử hóa cho kết quả tốt giúp AI sớm được triển khai trực tiếp trên các thiết bị. Giờ đây, có thể giảm yêu cầu về bộ nhớ của LLM bằng cách giảm độ chính xác của các tham số của chúng nhưng vẫn đảm bảo hiệu suất của AI ở mức độ chấp nhận được.
🧑‍💼 Các nhà nghiên cứu đang đạt được tiến bộ trong việc cá nhân hóa trên thiết bị. Representation fine-tuning (ReFT) điều chỉnh hoạt động bên trong của mô hình tại thời điểm suy luận để điều khiển hành vi của nó. ReFT đỏi hỏi ít hơn 15-65 lần tham số so với các phương pháp tinh chỉnh dựa trên trọng số, khiến nó phù hợp với các ứng dụng trên thiết bị.
🔗 Các mô hình lai kết hợp cơ chế chú ý với các cơ chế khác đang được quan tâm. Các mô hình này vẫn đảm bảo hoặc còn cải thiện độ chính xác, đồng thời giảm chi phí tính toán và dung lượng bộ nhớ.
🌱 Dữ liệu tổng hợp đang được áp dụng rộng rãi hơn, nhưng có những lo ngại về "model collapse", xảy ra khi các mô hình được huấn luyện trên quá nhiều dữ liệu tổng hợp.
🕸️ Dữ liệu web đang được công khai ở quy mô lớn. Hugging Face đã xây dựng một tập dữ liệu 15T token cho việc tiền huấn luyện LLM bằng cách sử dụng 96 CommonCrawl snapshots, tạo ra các LLM vượt trội hơn các mô hình đào tạo trên tập dữ liệu tiền huấn luyện mở khác.
🔍 Retrieval và embeddings đang được quan tâm nhờ tầm quan trọng của RAG.
🎯 Ngữ cảnh đã được chứng minh là một yếu tố quan trọng trong hiệu suất của RAG. Tuy nhiên, việc đánh giá RAG vẫn chưa được giải quyết.
⚡ Các phòng thí nghiệm tiên tiến đang đối mặt với tình trạng thiếu điện và đang nghiên cứu các biện pháp khắc phục. Google DeepMind đã đề xuất một thuật toán tối ưu hóa cho phép đào tạo diễn ra trên nhiều "cụm" thiết bị được kết nối lỏng lẻo, giảm nhu cầu trao đổi dữ liệu thường xuyên.
🏋️‍♀️ Các nhà nghiên cứu đang khám phá các phương pháp để giảm yêu cầu tính toán đào tạo. Google DeepMind đã phát triển JEST, công cụ chọn lọc các ví dụ đào tạo một cách linh hoạt dựa trên khả năng học của chúng.
🇨🇳 Các phòng thí nghiệm Trung Quốc đang đóng góp đáng kể cho nghiên cứu AI, dù đang chịu lệnh trừng phạt của Hoa Kỳ.
🎨 Các mô hình khuếch tán để tạo hình ảnh đang trở nên tinh vi hơn, nhờ các nhà nghiên cứu tìm ra những cải tiến giúp tăng chất lượng đồng thời mang lại hiệu quả cao hơn.
🧬 AlphaFold 3, phiên bản kế nhiệm của AlphaFold 2, giờ đây có thể mô hình hóa cách các loại thuốc phân tử nhỏ, DNA, RNA và kháng thể tương tác với các mục tiêu protein. Tuy nhiên, quyết định không phát hành mã nguồn của AlphaFold 3 đã gây tranh cãi, dẫn đến một cuộc đua để tạo ra một mô hình hoạt động đầy đủ.
🦠 DeepMind đã phát hành AlphaProteo, một mô hình tạo sinh có thể thiết kế các chất kết dính protein sub-nanomolar với ái lực tốt hơn gấp 3 đến 300 lần.
🔄 Phương pháp equivariance (đồng biến), vốn là một ý tưởng cốt lõi trong nghiên cứu AI, đang bị thách thức. Nghiên cứu gần đây cho thấy các mô hình không đồng biến có thể đạt được kết quả tốt hơn trong một số trường hợp.
🔬 Các mô hình nền tảng đang được phát triển trên nhiều lĩnh vực khoa học khác nhau, bao gồm sinh học, vật liệu vô cơ, hoạt động não bộ và khoa học khí quyển.
🏆 Một cuộc thi mới, giải thưởng ARC, nhằm mục đích tái tập trung ngành công nghiệp AI vào con đường hướng tới trí tuệ nhân tạo tổng quát (AGI).
🧩 LLM vẫn gặp khó khăn với các tác vụ lập kế hoạch và mô phỏng. Các nhà nghiên cứu đang khám phá các phương pháp mới để cải thiện khả năng lập kế hoạch và lập luận của những mô hình này.
🔎 Các thuật toán tìm kiếm chương trình (program search) đang mở ra những khám phá mới trong toán học.
📈 RL đang thúc đẩy cải tiến hiệu suất VLM.
🤖 Các nhà nghiên cứu đang khám phá các cách để đào tạo RL agent ở quy mô lớn bằng cách sử dụng các mô hình nền tảng.
🔬 Các nhà nghiên cứu đang bắt đầu tự động hóa việc nghiên cứu bằng cách sử dụng các mô hình nền tảng.
🤝 Các phương pháp Ensemble đang thúc đẩy cải tiến hiệu suất mạnh mẽ trong tạo mã.
🚗 Xe tự lái đang áp dụng nhiều phương thức hơn.
🎥 Segment Anything, mô hình phân đoạn hình ảnh ấn tượng của Meta, đã được mở rộng sang video.
🤖 Nghiên cứu robot lại đang trở nên phổ biến.
⚙️ Các mô hình khuếch tán đang thúc đẩy cải tiến trong việc tạo chính sách và hành động trong robot.
🔄 Các nhà nghiên cứu đang tìm cách mở rộng dữ liệu về thế giới thực của robot.
🍎 Apple Vision Pro đang nổi lên như một công cụ nghiên cứu robot cần phải có.
⚕️ Các mô hình đa phương thức được tinh chỉnh đang đạt được kết quả tiên tiến trong AI y tế.
💊 Các nhà nghiên cứu đang khám phá các cách để tạo dữ liệu tổng hợp trong y học.
🏢 AI đang được áp dụng vào các công cụ tự động hóa doanh nghiệp.
🌍 Cán cân quyền lực toàn cầu trong nghiên cứu AI nói chung vẫn không thay đổi, nhưng giới học thuật đang đóng góp nhiều hơn các công ty.
🟩 NVIDIA vẫn thống trị thị trường chip AI. Tuy nhiên, một số đối thủ cạnh tranh đang bắt đầu xuất hiện.
