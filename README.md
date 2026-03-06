# ☢️ Project Manhattan (codename: Silverplate)

> "Agora eu me tornei a Morte, a destruidora de mundos." — **@oppenheimer-j**, Project Lead.

## 📋 Visão Geral

Este repositório contém o código-fonte, esquemas de hardware e modelos físicos para o desenvolvimento de dispositivos de fissão nuclear em larga escala. O objetivo é encerrar a Segunda Guerra Mundial através de uma liberação súbita de energia térmica e cinética via decaimento radioativo rápido.

### ⚠️ Disclaimer

Este projeto é estritamente para fins de defesa. O uso não autorizado resultará em corte de verba imediato ou, mais provavelmente, em uma visita do General Groves e encarceramento em local não revelado.

---

## 🏗️ Arquitetura do Sistema

O projeto está dividido em dois "branches" principais de implementação:

### 1. `feature/little-boy` (Gun-type Assembly)

* **Mecanismo:** Disparo de um projétil de Urânio-235 contra um alvo de Urânio-235.
* **Status:** Stable.
* **Eficiência:** Baixa, mas confiável.

### 2. `feature/fat-man` (Implosion-type)

* **Mecanismo:** Compressão simétrica de um núcleo de Plutônio-239 usando lentes explosivas de alta precisão.
* **Status:** Experimental (Requer teste de integração em `trinity-site`).
* **Complexidade:** Alta. Requer sincronização de nanossegundos nos gatilhos.

---

## 🚀 Como Rodar (Deployment)

### Pré-requisitos

* **Hardware:** Pelo menos 64kg de Urânio enriquecido ou 6kg de Plutônio.
* **Infraestrutura:** Um bombardeiro B-29 modificado.
* **Ambiente:** Deserto do Novo México (para testes) ou coordenadas específicas no Pacífico.

### Variáveis de Ambiente

Certifique-se de configurar suas chaves secretas no arquivo `.env`:

```bash
CYLINDER_PRESSURE=critical
DETONATION_ALTITUDE=1900ft
SECRET_KEY=y0u_w1ll_n3v3r_gu3ss_th1s

```

### Comandos

Para iniciar a sequência de detonação:

```bash
./detonate --payload=plutonium --mode=implosion --target=classified

```

---

## 🧪 Física e Matemática

A energia liberada ($E$) segue a implementação padrão da biblioteca `Einstein_Relativity`:

$$E = mc^2$$

A massa crítica é calculada dinamicamente com base na pureza do material. Se a sua `k-effective` for menor que 1.0, o sistema entrará em *graceful shutdown* (também conhecido como "fizzile").

---

## 👥 Contribuidores Principais

* **@oppenheimer-j**: Gerenciamento de conflitos e citações em sânscrito.
* **@fermi-e**: Otimização de stacks de grafite (Chicago Pile-1).
* **@feynman-r**: Debugging de travas de segurança e bongôs.
* **@von-neumann**: Algoritmos de implosão e design de lentes explosivas.
* **@groves-gen**: Gerenciamento de deploys e segurança do repositório.

---

## 📝 Roadmap

* [x] Extração de Isótopos (Oak Ridge Cluster)
* [x] Teste de Unidade (Trinity Test)
* [ ] Deploy em Produção (Tinian Island)
* [ ] Documentação de Pós-Lançamento (Relatório Smyth)

---
