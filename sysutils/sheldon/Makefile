PORTNAME=	sheldon
DISTVERSION=	0.7.3
PORTREVISION=	0
CATEGORIES=	sysutils

MAINTAINER=	raphaelahrens@googlemail.com
COMMENT=	Fast, configurable, shell plugin manager
WWW=		https://github.com/rossmacarthur/sheldon

LICENSE=	APACHE20 MIT
LICENSE_COMB=	dual
LICENSE_FILE_APACHE20=	${WRKSRC}/LICENSE-APACHE
LICENSE_FILE_MIT=	${WRKSRC}/LICENSE-MIT

LIB_DEPENDS=	libgit2.so:devel/libgit2 \
		libssh2.so:security/libssh2

USES=		cargo localbase ssl

USE_GITHUB=	yes
GH_ACCOUNT=	rossmacarthur
GH_PROJECT=	sheldon
NO_TEST=	yes

CARGO_CRATES=	aho-corasick-0.7.20 \
		aho-corasick-1.0.1 \
		anstyle-1.0.0 \
		anyhow-1.0.71 \
		atty-0.2.14 \
		autocfg-1.1.0 \
		bitflags-1.3.2 \
		bstr-1.4.0 \
		bytes-1.4.0 \
		casual-0.2.0 \
		cc-1.0.79 \
		cfg-if-1.0.0 \
		clap-4.2.7 \
		clap_builder-4.2.7 \
		clap_complete-4.2.2 \
		clap_derive-4.2.0 \
		clap_lex-0.4.1 \
		combine-4.6.6 \
		constcat-0.3.0 \
		crossbeam-channel-0.5.8 \
		crossbeam-deque-0.8.3 \
		crossbeam-epoch-0.9.14 \
		crossbeam-utils-0.8.15 \
		ctor-0.1.26 \
		curl-0.4.44 \
		curl-sys-0.4.61+curl-8.0.1 \
		diff-0.1.13 \
		either-1.8.1 \
		errno-0.3.1 \
		errno-dragonfly-0.1.2 \
		fastrand-1.9.0 \
		fmutex-0.1.0 \
		fnv-1.0.7 \
		form_urlencoded-1.1.0 \
		git2-0.17.1 \
		globset-0.4.10 \
		globwalk-0.8.1 \
		goldie-0.4.3 \
		hashbrown-0.12.3 \
		heck-0.4.1 \
		hermit-abi-0.1.19 \
		hermit-abi-0.2.6 \
		hermit-abi-0.3.1 \
		home-0.5.5 \
		idna-0.3.0 \
		ignore-0.4.20 \
		indexmap-1.9.3 \
		instant-0.1.12 \
		io-lifetimes-1.0.10 \
		itertools-0.10.5 \
		itoa-1.0.6 \
		jobserver-0.1.26 \
		lazy_static-1.4.0 \
		libc-0.2.144 \
		libgit2-sys-0.15.1+1.6.4 \
		libssh2-sys-0.3.0 \
		libz-sys-1.1.9 \
		linux-raw-sys-0.3.7 \
		log-0.4.17 \
		maplit-1.0.2 \
		memchr-2.5.0 \
		memoffset-0.8.0 \
		num_cpus-1.15.0 \
		once_cell-1.17.1 \
		openssl-probe-0.1.5 \
		openssl-sys-0.9.87 \
		output_vt100-0.1.3 \
		percent-encoding-2.2.0 \
		pkg-config-0.3.27 \
		pretty_assertions-1.3.0 \
		proc-macro2-1.0.56 \
		quote-1.0.27 \
		rayon-1.7.0 \
		rayon-core-1.11.0 \
		redox_syscall-0.3.5 \
		regex-1.8.1 \
		regex-macro-0.2.0 \
		regex-syntax-0.7.1 \
		rustix-0.37.19 \
		ryu-1.0.13 \
		same-file-1.0.6 \
		schannel-0.1.21 \
		scopeguard-1.1.0 \
		serde-1.0.162 \
		serde_derive-1.0.162 \
		serde_json-1.0.96 \
		socket2-0.4.9 \
		strsim-0.10.0 \
		syn-1.0.109 \
		syn-2.0.15 \
		tempfile-3.5.0 \
		thiserror-1.0.40 \
		thiserror-impl-1.0.40 \
		thread_local-1.1.7 \
		tinyvec-1.6.0 \
		tinyvec_macros-0.1.1 \
		toml-0.5.11 \
		toml_edit-0.14.4 \
		unicode-bidi-0.3.13 \
		unicode-ident-1.0.8 \
		unicode-normalization-0.1.22 \
		unicode-width-0.1.10 \
		upon-0.5.0 \
		upon-0.6.0 \
		url-2.3.1 \
		vcpkg-0.2.15 \
		walkdir-2.3.3 \
		which-4.4.0 \
		winapi-0.3.9 \
		winapi-i686-pc-windows-gnu-0.4.0 \
		winapi-util-0.1.5 \
		winapi-x86_64-pc-windows-gnu-0.4.0 \
		windows-sys-0.42.0 \
		windows-sys-0.45.0 \
		windows-sys-0.48.0 \
		windows-targets-0.42.2 \
		windows-targets-0.48.0 \
		windows_aarch64_gnullvm-0.42.2 \
		windows_aarch64_gnullvm-0.48.0 \
		windows_aarch64_msvc-0.42.2 \
		windows_aarch64_msvc-0.48.0 \
		windows_i686_gnu-0.42.2 \
		windows_i686_gnu-0.48.0 \
		windows_i686_msvc-0.42.2 \
		windows_i686_msvc-0.48.0 \
		windows_x86_64_gnu-0.42.2 \
		windows_x86_64_gnu-0.48.0 \
		windows_x86_64_gnullvm-0.42.2 \
		windows_x86_64_gnullvm-0.48.0 \
		windows_x86_64_msvc-0.42.2 \
		windows_x86_64_msvc-0.48.0 \
		yansi-0.5.1


PLIST_FILES=	bin/${PORTNAME}

post-install:
	@${STRIP_CMD} ${STAGEDIR}${PREFIX}/bin/${PORTNAME}

.include <bsd.port.mk>
