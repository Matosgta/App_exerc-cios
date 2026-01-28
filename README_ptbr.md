# Biblioteca de Exercícios — PT-BR (400 exercícios)

Arquivo principal: exercises_ptbr_400.json

Schema (resumo):
- id: string
- nome_pt: string
- categoria: string (Força/Cardio/Core/Mobilidade/Alongamento)
- nivel: string (iniciante/intermediário/avançado)
- musculos_primarios: [muscle_id]
- musculos_secundarios: [muscle_id]
- equipamento: [equipment_id]
- movement_pattern: string
- force_type: string
- dificuldade: integer (1-5)
- tempo: string
- reps_range: string
- sets_range: string
- instrucoes: [strings]
- dicas: [strings]
- erros_comuns: [strings]
- contraindicacoes: [strings]
- variacoes: [{nome, notas}]
- image_url: string (Unsplash)
- video_url: string (Pexels)
- tags: [string]
- created_at / updated_at: timestamps ISO8601

Mídia:
- Imagens: URLs do Unsplash (royalty-free).
- Vídeos: URLs do Pexels (royalty-free).

Gerado em 2026-01-28T21:33:08Z.
